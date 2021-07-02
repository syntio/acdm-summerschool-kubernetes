# SummerSchoolK8s
Repo made for Syntio summer school. It contains simple nginx hello world web app with a dockerfile, kubernetes deployments and github action workflow.
Workflow is set to on push, which means you can do some simple change, push it and you will see this code in action.

The push triggers a workflow that builds a docker image and pushes it to an azure container registry. Then, nside of a kubernetes cluster on azure kuberentes service yaml files are applied and the web app is deployed and can be connected to through browser with ip and port.    

Congratulations!
