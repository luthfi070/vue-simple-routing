<template>
	<div>
	<h1>Ini Form Kelas</h1>
	<router-link to="/kelas">Balik Lagi</router-link>
	<center>
  <br><br>
  <fieldset>
  Kelas:
<input type="text" name="kls">
<br>
Wali Kelas:
<input type="text" name="wk">
<br>
Jumlah Murid:
<input type="text" name="jm">
<br>
Jurusan:
<select>
  <option value="TOI">TOI</option>
  <option value="RPL">RPL</option>
  <option value="TKJ">TKJ</option>
  <option value="AV">AV</option>
  <option value="MM">MM</option>
  <option value="TITL">TITL</option>
</select>
</fieldset>
</center>
	</div>
	</template>

	<script>
	export default {
	}
	</script>