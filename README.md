# Node.js MongoDB Rest CRUD API
## Define Routes
 - The following table shows overview of the Rest APIs that will be exported:
<table>
<thead>
<tr>
<th>Methods</th>
<th>Urls</th>
<th>Actions</th>
</tr>
</thead>
<tbody>
<tr>
<td>GET</td>
<td>api/tutorials</td>
<td>get all Tutorials</td>
</tr>
<tr>
<td>GET</td>
<td>api/tutorials/:id</td>
<td>get Tutorial by <code>id</code></td>
</tr>
<tr>
<td>POST</td>
<td>api/tutorials</td>
<td>add new Tutorial</td>
</tr>
<tr>
<td>PUT</td>
<td>api/tutorials/:id</td>
<td>update Tutorial by <code>id</code></td>
</tr>
<tr>
<td>DELETE</td>
<td>api/tutorials/:id</td>
<td>remove Tutorial by <code>id</code></td>
</tr>
<tr>
<td>DELETE</td>
<td>api/tutorials</td>
<td>remove all Tutorials</td>
</tr>
<tr>
<td>GET</td>
<td>api/tutorials/published</td>
<td>find all published Tutorials</td>
</tr>
<tr>
<td>GET</td>
<td>api/tutorials?title=[keyword]</td>
<td>find all Tutorials which title contains <code>'keyword'</code></td>
</tr>
</tbody>
</table>