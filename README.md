# kubernetes_prompt 

|     NAME        |     PROMPT    |  EXAMPLE                                                  |    
| --------------- | ------------- |---------------------------------------------------------- |
| Simple Pod      | kind: Pod     | [app.yaml](yaml/app.yaml)                                 |
| LivenessProbe   | kind: Pod     | [app-livenessProbe.yaml](/yaml/app-livenessProbe.yaml)    |
| ReadinessProbe  | kind: Pod     | [app-readinessProbe.yaml](/yaml/app-readinessProbe.yaml)  |
| VolumeMounts    | kind: Pod     | [app-volumeMounts.yaml](/yaml/app-volumeMounts.yaml)      |
| CronJob         | kind: CronJob | [app-cronjob.yaml](/yaml/app-cronjob.yaml)                |
| Job             | kind: Job     | [app-job.yaml](/yaml/app-job.yaml)                        |
| Multicontainer  | kind: Pod     | [app-multicontainer.yaml](/yaml/app-multicontainer.yaml)  |
| Limit resources | kind: Pod     | [app-resources.yaml](/yaml/app-resources.yaml)            |
| Secret          | kind: Pod     | [app-secret-env.yaml](/yaml/app-secret-env.yaml)          |
