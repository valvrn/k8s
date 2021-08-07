#Steps

1. kubectl create ns kubedoom
2. kubectl apply -f doomservice.yaml
3. kubectl.exe apply -f kubedoom.yaml
4. kubectl.exe get pod -n kubedoom
5. kubectl.exe port-forward <pod-name> <local-port>:5900 -n kubedoom
6. vncviewer viewer localhost:<local-port>
6.1 pass- idbehold
