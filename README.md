 LTC Spinn Boot

<dl>
  <dt>Deskripsi</dt>
  <dd>Ini adalah Tools Untuk Nuyul Aplikasi Free LTC Spinner</dd>

  <dt>Cara Install</dt>
</dl>
<pre><code>apt update && apt upgrade -y
pkg install nano 
pkg install git
pkg install php
cd FreeLTCSpin
nano config.php
php LTCSpin.php
</code></pre>
<dl>
  <dd>Edit Config.php</dd>
  <dd>ganti dengan data punya anda</dd>
</dl>
<pre><code>
&lt;?php
//Email 
$email = "xxxxxxxxxxxx@gmail.com";
//Device ID
$deviceid = "xxxxxxxxxxxxxxxxxxxxxxxxxxxx";
?&gt;
</code></pre>
<dl>
