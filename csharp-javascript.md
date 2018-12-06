# Collection
## Initialization
<table>
  <tr>
    <th>
    Collection
    </th>
    <th>
    C#
    </th>
    <th>
    Javascript
    </th>
  </tr>
  <tr>
    <td>
    Array
    </td>
    <td>
    
```C#
int[] numbers = { 1, 2, 3 }
string[] names = { "Robert", "Larry" };
```

</td>
<td>

```Javascript
const numbers = [1, 2, 3];
const names = ['Robert', 'Larry'];
```
    
</td>
</tr>
<tr>
<td>Set</td>
<td>

```C#
var nameSet = new HashSet<string>(names);
var nameSet2 = new HashSet<string>()
{
    "Robert", 
    "Larry"
};
```

</td>
<td>

```javascript
const nameSet = new Set(names);
const nameSet2 = new Set(['Robert', 'Larry']);
```
</td>
</tr>
<tr>
<td></td>
<td></td>
<td></td>
</tr>
</table>


## Looping
<table>
  <tr>
    <th>
    C#
    </th>
    <th>
    Javascript
    </th>
  </tr>
<tr>
<td>

```C#
foreach (var name in names)
{
    Console.WriteLine(name);
}
```
</td>
<td>

```Javascript
for (let name of names) {
  console.log(name);
}
```
</td>
</tr>
</table>
