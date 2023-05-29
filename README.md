# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Clone the github repository.

### Step 2:
Create a new Django project

### Step 3:
Write the needed HTML code.

### step 4:
Run the Django server and execute the HTML files.

## Code:
### html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>The city of Attack on titan</title>
<style>
body{
  background-image: url("/static/images/aot 1.png");
  background-attachment: fixed;
  background-size: 100% 100%;
}
</style>
</head>
<body>
<h1 align="center">
<font color="red"><b>BERMUDA</b></font>
</h1>
<center>
<img src="/static/images/nearme pic1.png" usemap="#MyCity" height="812" width="1592">
<img src="/static/images/nearme pic2.png" usemap="#MyCity" height="773" width="1545">
<map name="MyCity">
<area shape="circle" coords="612,664,25" href="/static/html/marleybeach.html" title="Marley Beach">
<area shape="circle" coords="239,715,25" href="/static/html/marleybeach.html" title="Marley Beach">
<area shape="circle" coords="1018,126,25" href="/static/html/armin.html" title="Armin Arlert's Library">
<area shape="circle" coords="144,746,25" href="/static/html/cliffs.html" title="Cliffs of Marley">
<area shape="circle" coords="330,450,25" href="/static/html/levi.html" title="Levi Ackerman's Tea Shop">
<area shape="circle" coords="500,450,25" href="/static/html/annie.html" title="Annie's Crystal">
</map>
</center>
<h3 align="left">
<font color="green"><b>The places that have information in this map are:</b></font>
</h3>
<h3 align="center">
<font color="white"><b>[Marley Beach]</b></font>
</h3>
<h3 align="center">
<font color="white"><b>[Armin Arlert's Library]</b></font>
</h3>
<h3 align="center">
<font color="white"><b>[Cliffs of Marley]</b></font>
</h3>
</h3>
<h3 align="center">
<font color="white"><b>[Levi Ackerman's Tea Shop]</b></font>
</h3>
</h3>
<h3 align="center">
<font color="white"><b>[Annie's Crystal]</b></font>
</h3>
</center>
<h3 align="right">
<font color="blue"><b>A.ASHWIN KUMAR (22001702)</b></font>
</h3>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Female Titan</title>
<style>
body{
  background-image: url("/static/images/aot 1.png");
  background-attachment: fixed;
  background-size: 100% 100%;
}
</style>
</head>
<h1 align="center">
<font color="lime"><b>Annie Leonhart</b></font>
</h1>
<h3 align="center">
<font color="purple"><b>former member of the Military Police Brigade</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5" color="cyan">
She possessed the ability to transform into a Titan known as the Female Titan. Trained from an early age by her father,[12] she is selected as one of Marley's Warriors. In the year 845, she is sent on a mission to retrieve the Founding Titan, along with fellow Warriors Reiner Braun, Bertolt Hoover, and Marcel Galliard. As the Female Titan, she serves as a major antagonist prior to her defeat, at which point she crystallizes herself and is left in a comatose state.[13] She was held underground in the custody of the Survey Corps for approximately four years before escaping during a battle between the Military, the Yeagerists, and the forces of Marley.
</font>
</p>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>CLOSSAL TITAN</title>
<style>
body{
  background-image: url("/static/images/aot 2.png");
  background-attachment: fixed;
  background-size: 100% 100%;
}
</style>
</head>
<h1 align="center">
<font color="red"><b>Armin Arlert</b></font>
</h1>
<h3 align="center">
<font color="yellow"><b>15th and current commander of the Survey Corps</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5" color="green">
Armin originally lived in the Shiganshina District of Wall Maria. After his parents were executed for attempting to escape the Walls, he was left to live with his grandfather.One day, after the latest in a series of beatings by bullies, Armin sat against a building, crying. Another boy, Eren Yeager, appeared around the corner with a shady look on his face. Eren asked Armin why he never fought back, and claimed that that was why they treated him like that; he then asked him if he wanted to be on the losing side forever. Armin then claimed that he was not losing by not running away. Eren then asked for his name, and the two began a friendship.
</font>
</p>
<h2 align="center">
    <font color="red">
    Titan form
    </font>
</h2>
<p align="justify">
<font face="Tahoma" size="5" color="white">
In his Colossus Titan form, Armin is entirely skinless and is extremely tall, similar to Bertolt's Titan. His Titan has elongated, skinny arms reaching past its knees and very muscular legs with short thick feet. His Titan's feet are shaped so that it can stand without falling over due to its proportions and height. Armin's Titan's upper body is also fairly skinny, with an exposed rib cage on the front and sides. Its face is missing a nose and almost all of its skin, which is replaced by bare bone. 
</font>
</p>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>cliffs of Marley</title>
<style>
body{
  background-image: url("/static/images/aotbg1.png");
  background-attachment: fixed;
  background-size: 100% 100%;
}
</style>
</head>
<h1 align="center">
<font color="red"><b>cliffs of Marley</b></font>
</h1>
<h3 align="center">
<font color="red"><b>paradise ISLAND</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
About 1,200 years ago, the large Marleyan city of Lago was destroyed by Titans of the Eldian Empire over the course of a single day. The Titans would continue their advance and went on to commit "The Devastation of Monte" and "The Ravaging of Valle" which resulted in the deaths of hundreds of thousands of Marleyans.[10] Grisha Yeager claimed these are all lies;[11] however, he was in denial of Eldia's brutal history of war and slavery.
</font>
</p>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Captain Levi the squad captain</title>
<style>
body{
  background-image: url("/static/images/levipic.jpg");
  background-attachment: fixed;
  background-size: 100% 100%;
}
</style>
</head>
<h1 align="center">
<font color="red"><b>Levi Ackerman</b></font>
</h1>
<h3 align="center">
<font color="cyan"><b>the squad captain of the Special Operations Squad within the Survey Corps and is widely known as humanity's strongest soldier.</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5" color="MediumSpringGreen">
Levi is seen leaving Trost District, along with the rest of the Survey Corps, on the 56th Expedition Beyond the Walls—the same day the Colossus Titan attacks the district.

While on the expedition, Levi sees a soldier caught in the jaws of a nearby Titan and kills it. As more Titans approach, Levi orders Petra Ral to take care of the injured soldier while he takes care of the remaining Titans. After clearing the immediate area, Levi checks on the injured soldier, who is quickly succumbing to his injuries. In an attempt to comfort the scout in his dying moments, Levi assures him that he has done his duty well. As the soldier dies, Erwin arrives and informs Levi that they are returning to Trost. Levi is unwilling to turn back so soon, is forced to concede when Erwin informs him that Wall Rose has possibly been breached.
</font>
</p>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Marley beach</title>
<style>
body{
  background-image: url("/static/images/aotbg2.jpeg");
  background-attachment: fixed;
  background-size: 100% 100%;
}
</style>
</head>
<h1 align="center">
<font color="red"><b>Marley beach</b></font>
</h1>
<h3 align="center">
<font color="blue"></body><b>The dark place of Marleyans</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5" color="black">
<b>
Marley is a nation located beyond the Walls and across the ocean from Paradis Island.Marley was a powerful nation in ancient times; however, around 2,000 years ago, a slave of the Eldians named Ymir gained the power of the Titans. King Fritz used her abilities to defeat Marley and force their surrender. One of the Marleyans attempted to assassinate Fritz several years after their defeat, but Ymir intervened and was killed instead. After Ymir's death, her power was split and passed down to her descendants in the form of the Nine Titans, who subsequently built the Eldian Empire. Using the Titans, the Eldians waged war against Marley and many other nations, utterly destroying them and obtaining complete rule over the continental mainland. This is considered to be the start of the Dark Ages
</b>
</font>
</p>
</body>
</html>
```
## Output:
![op1](https://github.com/ASHWINKUMAR2903/places-around-me/assets/119407186/805839f7-cc3b-4bb5-ad65-bebbae146385)
![op2](https://github.com/ASHWINKUMAR2903/places-around-me/assets/119407186/343889bd-5ceb-4fcc-8fd4-5fbce11d5d9d)
![marleyop](https://github.com/ASHWINKUMAR2903/places-around-me/assets/119407186/668b7ad0-b0e5-41f3-8f74-39e789e7e12e)
![arminop](https://github.com/ASHWINKUMAR2903/places-around-me/assets/119407186/9781e88b-1607-42d7-b853-3e679f0921a4)
![annieop](https://github.com/ASHWINKUMAR2903/places-around-me/assets/119407186/149a08d5-fa91-4ec8-9f74-1d84f27f96d6)
![cliff](https://github.com/ASHWINKUMAR2903/places-around-me/assets/119407186/3c3d47b0-ced8-4499-94ff-ddd3769c0ec1)
![leviop](https://github.com/ASHWINKUMAR2903/places-around-me/assets/119407186/2cd700cf-1a2c-41a1-a2d1-475350e449dc)


## Result:
Thus the program for Places Around me is executed Successfully.
