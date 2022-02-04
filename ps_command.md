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




