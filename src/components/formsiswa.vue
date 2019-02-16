<template>
	<div>
	<h1>Ini Form Siswa</h1>
	<router-link to="/siswa">Balik Lagi</router-link>
	<center>
  <br><br>
  <fieldset>
  nama:
<input type="text" name="nama">
<br>
kelas:
<input type="text" name="kelas">
<br>
Jenis Kelamin:
<select>
  <option value="L">Laki-Laki</option>
  <option value="P">Perempuan</option>
</select>
<br>
tanggal lahir:
<input type="date" name="tanggal">
</fieldset>
</center>
	</div>
	</template>

	<script>
	export default {
	}
	</script>