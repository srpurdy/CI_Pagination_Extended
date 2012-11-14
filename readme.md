<h1>Extended Codeigniter Pagination Class</h1>
<p>This extended class gives the ability to render links like below</p>
<small>[1][2][3]...[7][8][9]...[20][21][22]</small>
<p>It's suggested you disable first and last links by setting them to FALSE when constructing pages with the pagination class. As these are redundant with this extended class.</p>

<h1>Example Usage</h1>
<pre>
$config['show_first_int'] = '3';
$config['show_last_int'] = '3';
</pre>