<h1>String</h1>
<br/>

<h3>StringBuilder</h3>
<br/>
<li>Using "System.Text" import.</li>
<li>You can print a text.</li>
<pre>
<code>
  public override string ToString()
  {
    StringBuilder sb = new StringBuilder();
    sb.AppendLine("List of strings: ");
    sb.AppendLine("01");
    sb.Append(" - Naruto");
    sb.AppendLine("02");
    sb.Append(" - Kakashi");
    return sb.ToString();
 }
</code>
</pre>
<br/>
<p>This method will return: </p>
<pre>
<code>
 <p>List of strings:</p>
 <p>01 - Naruto</p>
 <p>02 - Kakashi</p>
</code>
</pre>
