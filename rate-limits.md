# Rate Limiting
To prevent platform abuse, we have incorporated various rate limits on a per api as well as per function level.

<table>
<thead>
<tr>
<th>
Event
</th>
<th>
Rate Limits
</th>
</tr>
</thead>
<tbody>
<tr>
<td>Create dynamo network</td>
<td>3 operations/min</td>
</tr>
<tr>
 <td>Create privatehive network</td>
 <td>3 operations/min</td>
</tr>
<tr>
<td> Paymeter APIs</td>
<td>120 req/min</td>
</tr>
<tr>
<td>Hyperion APIs</td>
<td>120 req/min</td>
</tr>
<tr>
<td>Platform APIs</td>
<td>180 req/min</td>
</tr>
</tbody>
</table>

The timeout for each operation expires individually after the interval.
