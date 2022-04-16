# solo-gloo-demo
## A simple demo to show more about solo.io Gloo Edge demo. 
#### Gloo Edge is a feature-rich, Kubernetes-native ingress controller, and next-generation API gateway. Gloo Edge is exceptional in its function-level routing; its support for legacy apps, microservices and serverless; its discovery capabilities; its numerous features; and its tight integration with leading open-source projects. Gloo Edge is uniquely designed to support hybrid applications, in which multiple technologies, architectures, protocols, and clouds can coexist.

### Many good and useful features because of underneath envoy, e.g. **Data Loss Prevention (DLP).**

e.g. DLP set at **50%** in DLP masking, see image 1 config: ![50% masking DLP config sample ](https://github.com/leewalter/solo-gloo-demo/blob/main/pictures/dlp1-50percent.jpg "DLP masking at 50% config example")
 
 image2 outputs with 50% masked:  ![50% masking DLP config sample ](https://github.com/leewalter/solo-gloo-demo/blob/main/pictures/dlp1-50percent-output.jpg "DLP masking at 50% output example")

 If I changed it to **90%**, then image 3 config: ![90% masking DLP config sample ](https://github.com/leewalter/solo-gloo-demo/blob/main/pictures/dlp2-90percent.jpg "DLP masking at 90% config example")
 
 then output will show 90% masked at image 4:  ![90% masking DLP config sample ](https://github.com/leewalter/solo-gloo-demo/blob/main/pictures/dlp2-90percent-ouput.jpg "DLP masking at 90% output example")
