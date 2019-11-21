# Practice Queries

## 1. SELECT

**Query :-**  How to query list of actors with metadata in the database.

**Solution :-**

<style>
table {
    width:100%;
}
th{
    width:600px;
}
.foo table .code{
    height:200px;
    width:100px;
}
</style>
<div class="foo">
<table>
  <tr>
    <th>Movie Database</th>
    <th>How will you use it in datalake</th>
  </tr>
  <tr class="code">
    <td>
    <pre style="margin: 0; line-height: 125%"><span style="color: #008800; font-weight: bold">SELECT</span> <span style="color: #333333">*</span> <span style="color: #008800; font-weight: bold">FROM</span> actor
    </pre>
    </td>
    <td>I will use it to extract data from <b>air</b> table.</td>
  </tr>
</table>
</div>

## 2. SELECT with specific columns or fields

**Query :-**  can you query only actor_name and gender from the database ?

**Solution :-**

<style>
table {
    width:100%;
}
th{
    width:600px;
}
.foo table .code{
    height:200px;
    width:100px;
}
</style>
<div class="foo">
<table>
  <tr>
    <th>Movie Database</th>
    <th>How will you use it in datalake</th>
  </tr>
  <tr class="code">
    <td>
    </td>
    <td>
    </td>
  </tr>
</table>
</div>

## 3. SELECT with WHERE

**Query :-**  can you query only male actors ?

**Solution :-**

<style>
table {
    width:100%;
}
th{
    width:600px;
}
.foo table .code{
    height:200px;
    width:100px;
}
</style>
<div class="foo">
<table>
  <tr>
    <th>Movie Database</th>
    <th>How will you use it in datalake</th>
  </tr>
  <tr class="code">
    <td>
    </td>
    <td>
    </td>
  </tr>
</table>
</div>

## 4. Renaming Column (Aliases)

**Query :-**  can you query only male actors with renaming columns act_name as `Actor Name` and act_gender as `Gender`

**Solution :-**

<style>
table {
    width:100%;
}
th{
    width:600px;
}
.foo table .code{
    height:200px;
    width:100px;
}
</style>
<div class="foo">
<table>
  <tr>
    <th>Movie Database</th>
    <th>How will you use it in datalake</th>
  </tr>
  <tr class="code">
    <td>
    </td>
    <td>
    </td>
  </tr>
</table>
</div>

## 5. ORDER BY (Aliases)

**Query :-**  can you query movie_title and movie_year and then sort year either desc or desc.

**Follow up :-**

1. can you sort by movie_title and then with year.
2. Can you apply where condtion and order by at a time.

**Solution :-**

<style>
table {
    width:100%;
}
th{
    width:600px;
}
.foo table .code{
    height:200px;
    width:100px;
}
</style>
<div class="foo">
<table>
  <tr>
    <th>Movie Database</th>
    <th>How will you use it in datalake</th>
  </tr>
  <tr class="code">
    <td>
    </td>
    <td>
    </td>
  </tr>
</table>
</div>

## 6. DISTINCT

**Query :-**  I want to see all the different roles that are availiable without duplicates.

**Solution :-**

<style>
table {
    width:100%;
}
th{
    width:600px;
}
.foo table .code{
    height:200px;
    width:100px;
}
</style>
<div class="foo">
<table>
  <tr>
    <th>Movie Database</th>
    <th>How will you use it in datalake</th>
  </tr>
  <tr class="code">
    <td>
    </td>
    <td>
    </td>
  </tr>
</table>
</div>

## 7. AND

**Query :-**  I want to see the movie details with the name of `Verito` that's directed in the year `1994`

**Solution :-**

<style>
table {
    width:100%;
}
th{
    width:600px;
}
.foo table .code{
    height:200px;
    width:100px;
}
</style>
<div class="foo">
<table>
  <tr>
    <th>Movie Database</th>
    <th>How will you use it in datalake</th>
  </tr>
  <tr class="code">
    <td>
    </td>
    <td>
    </td>
  </tr>
</table>
</div>

## 8. OR

**Query :-**   I want to see a list of movie_titles that directed in either 2006 or 1994.

**Solution :-**

<style>
table {
    width:100%;
}
th{
    width:600px;
}
.foo table .code{
    height:200px;
    width:100px;
}
</style>
<div class="foo">
<table>
  <tr>
    <th>Movie Database</th>
    <th>How will you use it in datalake</th>
  </tr>
  <tr class="code">
    <td>
    </td>
    <td>
    </td>
  </tr>
</table>
</div>

## 9. NOT

**Query :-** Query all the movie_titles excluding movies directed in greater than 2000.

**Solution :-**

<style>
table {
    width:100%;
}
th{
    width:600px;
}
.foo table .code{
    height:200px;
    width:100px;
}
</style>
<div class="foo">
<table>
  <tr>
    <th>Movie Database</th>
    <th>How will you use it in datalake</th>
  </tr>
  <tr class="code">
    <td>
    </td>
    <td>
    </td>
  </tr>
</table>
</div>

## 10. BETWEEN

**Query :-** Query all the movie_titles that are directed between 1994 and 2002.

**Solution :-**

<style>
table {
    width:100%;
}
th{
    width:600px;
}
.foo table .code{
    height:200px;
    width:100px;
}
</style>
<div class="foo">
<table>
  <tr>
    <th>Movie Database</th>
    <th>How will you use it in datalake</th>
  </tr>
  <tr class="code">
    <td>
    </td>
    <td>
    </td>
  </tr>
</table>
</div>

## 10. IN

**Query :-** Query all the mov_id,  mov_title, mov_year, mov_lang for movies `Vertigo` , `Innocents` and `Wings`

**Solution :-**

<style>
table {
    width:100%;
}
th{
    width:600px;
}
.foo table .code{
    height:200px;
    width:100px;
}
</style>
<div class="foo">
<table>
  <tr>
    <th>Movie Database</th>
    <th>How will you use it in datalake</th>
  </tr>
  <tr class="code">
    <td>
    </td>
    <td>
    </td>
  </tr>
</table>
</div>

## Extra Functions

<style>
table {
    width:100%;
}
th{
    width:600px;
}
.foo table .code{
    height:200px;
    width:100px;
}
</style>
<div class="foo">
<table>
  <tr>
    <th>String Functions</th>
    <th>Numeric Functions</th>
    <th>Date Functions</th>
    <th>Advanced Functions</th>
  </tr>
  <tr class="code">
    <td>
        <ul>
            <li> LEN , CHAR_LENGTH, CHARACTER_LENGTH</li>
            <li>CONCAT</li>
            <li>CONCAT_WS</li>
            <li>FORMAT</li>
            <li>LCASE, LOWER</li>
            <li>UCASE, UPPER</li>
            <li>TRIM</li>
            <li>LEFT</li>
            <li>RIGHT</li>
            <li>MID, SUBSTR</li>
            <li>INSTR</li>
        </ul>
    </td>
    <td>
        <li>ABS</li>
        <li>MAX</li>
        <li>MIN</li>
        <li>CEIL</li>
        <li>FLOOR</li>
        <li>SUM</li>
        <li>COUNT</li>
        <li>ROUND</li>
    </td>
    <td>
        <ul>
            <li><a href="https://www.w3schools.com/sql/sql_ref_mysql.asp">Important Date functions</a>
        </ul>
    </td>
    <td>
        <ul>
            <li>CASE</li>
            <li>CAST, CONVERT</li>
            <li>IF</li>
            <li>IFNULL</li>
            <li>ISNULL</li>
        </ul>
    </td>
  </tr>
</table>
</div>

