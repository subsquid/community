
This dashboard presents the basic metrics that you will need to monitor the status of your node.

 1.  chain heights
 2.  current archive head block
 3.  average time for block ingestions
 4.   timing for gRPC requests
 5.  standard Node.js system metrics


How to use it?

You must have Grafana deployed locally, and the data source must be deployed. 
The data source gives metrics, Grafana visualizes the incoming data, for the convenience of the eyes.
The Grafana must be deployed independently and will be located http://localhost:3000
you need to download the file Subsquid-1647841152567.json and import it to yourself in grafana

![Снимок экрана от 2022-03-25 10-16-13](https://user-images.githubusercontent.com/64533602/160073148-8d5ac500-5450-4ac4-804d-abd2c0cc1dcf.png)

Next, you need to download it, and you will see how your host's metrics went

![Снимок экрана от 2022-03-25 10-21-41](https://user-images.githubusercontent.com/64533602/160073618-22f9997a-4186-40b2-b915-129551e2d141.png)

