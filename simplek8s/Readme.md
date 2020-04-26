Inside client-pod.yaml, it defines the labels "component: web".  
And inside client-node-port.yaml, it specify the selector according to the label above "component: web".
You can use any key and value combination.  

Inside client-node-port.yaml, targetPort points to Pod port, containerPort: 3000.  
