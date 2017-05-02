<table>
  <tbody style="vertical-align: top;">
    <tr>
      <td>
        {% for post in site.posts %}
          <h2>{{ post.date | date: "%-m/%-d/%Y" }} - {{ post.title }}</h2>
          {{ post.content }}
          <hr>
        {% endfor %}
      </td>
      <td width=470px>
        <p>
          What Every Scout Should Know:
        </p>
        <p>
          Scout Oath:<br>
          “On my honor, I will do my best<br> 
          To do my duty to God and my country and to obey the Scout Law;<br>
          To help other people at all times;<br>
          To keep myself physically strong, mentally awake, morally straight.”<br>
        </p>
        <p>
           Scout Law:<br>
      “A Scout is Trustworthy, Loyal, Helpful, Friendly, Courteous, Kind, Obedient, Cheerful , Thrifty, Brave, Clean, Reverent.”
        </p>
        <p>
          Outdoor Code:<br>
      “As an American I will do my best to: <br>
         Be clean in my outdoor manners.<br>
         Be careful with fire.<br>
         Be considerate in the outdoors.<br>
         Be conservation minded.”<br>
        </p>
        <p>
          Scout Motto:<br>
      “Be prepared!”<br>
        <br>
      Scout Slogan”<br>
      “Do a good turn daily!”
        </p>
      </td>
    </tr>
  </tbody>
</table>
