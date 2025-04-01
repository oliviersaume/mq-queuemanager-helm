# mq-queuemanager-helm


This repository contains a simple helm chart used to get familiar with the deployment of a IBM queue manager in a Kubernetes cluster (Docker Desktop based - Microsoft Windows).
The deployment will be done in the defautl namespace. This will be updated in a later release.
It uses a deployment instead of a statefulSet.

To install it : `helm install dev .\mq-queuemanager-helm`

To check if it was  deployed : `helm list`

Then, check that the pod was successfully started and is running : `kubectl get pods`
