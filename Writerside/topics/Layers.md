# Infrastructure and application Layers

<p>
It's important to note which layer you want the **Frock** on.
</p>

<p>
We have developed an understanding of what an infrastructure layer is and what an application layer is. Let's try to understand and compare them using the simple table below:
</p>

<table>
<tr>
<td>Infrastructure layer</td>
<td>Application layer</td>
</tr>

<tr>
<td>Setting up and support Grafana in k8s cluster</td><td>Setting up boards with metrics of services in Grafana</td>
</tr>

<tr>
<td>Setting up and support k8s cluster</td><td>Deploying business application to k8s cluster</td>
</tr>

<tr>
<td>Setting up and support ELKF</td><td>Accessing applications logs</td>
</tr>

<tr>
<td>Common system metrics for Nginx Ingress</td><td>Custom application metrics</td>
</tr>

<tr>
<td>Setting up fault-tolerant database</td><td>Setting up temp not fault-tolerant database for test environment</td>
</tr>

<tr>
<td>Setting up workers for CI/CD</td><td>Setting up and launching autotests for your application on CI/CD</td>
</tr>

</table>

### Frock.dev made for the application layer. 

<p>
Frock comes to your aid at the application level. It will be able to support full application development cycle,
but will not be able to set up replication on your production PostgreSQL (for example).
</p>