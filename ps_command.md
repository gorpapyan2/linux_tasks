ps aux | awk '{print$1,$2,$11}'

USER PID COMMAND
root 1 /sbin/init
root 2 [kthreadd]
root 3 [rcu_gp]
root 4 [rcu_par_gp]
root 6 [kworker/0:0H-events_highpri]
root 8 [mm_percpu_wq]
root 9 [rcu_tasks_rude_]
root 10 [rcu_tasks_trace]

...............................


ps -eo pid,user,command


PID USER     COMMAND
      1 root     /sbin/init splash
      2 root     [kthreadd]
      3 root     [rcu_gp]
      4 root     [rcu_par_gp]
      6 root     [kworker/0:0H-events_highpri]
      8 root     [mm_percpu_wq]
      9 root     [rcu_tasks_rude_]
     10 root     [rcu_tasks_trace]

...........................






