<html>
<head>
<title></title>
<style>
table {
  bgcolor: black;
  color: white;
  border: 1px solid white;
  text-align: center;
}
.wrapper {
  background-color: black;
  color: white;
  font-family: Arial;
}
.header {
padding-top: 20px;
padding-bottom: 80px;
padding-left: 10px;
margin-left: auto;
margin-right: auto;
font-size: 48px;
font-weight: bold;
font-family: Courier;
color: white;
}
.name {
  font-size: 18px;
  font-weight: bold;
}
.series {
  font-size: 14px;
  font-style: italic;
}
.kv {
  font-size: 14px;
  font-weight: bold;
  padding-left: 10px;
  padding-right: 10px;
}
</style>
</head>
<div class="wrapper">
  <div class="header">the garden of waifu</div>
  <table>
    <tbody>
      <tr>
        <td class="name">
          Name
        </td>
      </tr>
      <tr>
        <td class="series">
          Series
        </td>
      </tr>
      <tr>
        <td class="kv">
          Kakera Value
        </td>
      </tr>
      <tr>
        <td>
          Image
        </td>
      </tr>
    </tbody>
  </table>
</div>

<script>
var waifu1 = {name:"Mai Sakurajima", series:"Seishun Buta Yarou wa Bunny Girl Senpai no Yume wo Minai - Rascal Does Not Dream of Bunny Girl Senpai", kakera:1256, image:"w1"};
var waifu2 = {name:"Mashiro Shiina", series:"Sakura-sou no Pet na Kanojo - The Pet Girl of Sakurasou", kakera:742, image:"w2"};
var waifu3 = {name:"Asuna Yuuki", series:"Sword Art Online", kakera: 1378, image:"w3"};

var waifus = [waifu1, waifu2, waifu3]

document.getElementById("name").innerHTML = waifus[0].name;

</script>
</html>
