



<img width="2048" height="800" alt="AEX" src="https://github.com/user-attachments/assets/feaa00c9-1bac-4e12-b379-20f2de87b978" />

# _After-Expand (AEX) — Exoplanet Expansion Pack_

_“来了，爱了，给Ta一颗星星，走了”_
_<p align="right">- 《三体 III 死神永生》 </p>_

***

After-Expand, also known as After-ExoPlanet (AEX), is an exoplanet expansion pack designed for the stock game, RealSolarSystem (RSS), or my AfterSolarSystem mod.
You may consider it the spiritual successor to RealExoPlanet (REX) or RealExpand.
AEX includes everything from REX and adds more than 10 additional exoplanetary systems, all updated using the latest available scientific data.
Although the name contains the word “After”, which might make you think it represents a future era, this is actually one of the mod’s defining features —

⭐ ***Timeline Overlap System***

Inside the AfterSolarSystemExpand directory, you will find a file named **Settings.cfg**

The parameter:    allows you to choose the timeline of the star systems.

- ***False (default): Present-day, real-time exoplanet data***
- ***True: The star systems are shifted 7 billion years into the future***

## 🤔 *Why is the folder named **“AfterSolarSystemExpand”**?*

The name may seem unrelated to its content, but there is historical context:

AEX was originally created by a friend, intended as an expansion for AfterSolarSystem.
Later, I joined the development and kept adding more systems.
By the time the project expanded into a full exoplanet mod, the folder name could no longer be changed without causing issues.

As a result, you might get the impression that the mod is mislabeled — but rest assured, you downloaded the right thing!

## 🔭 **Improvements Over the 2020 RealExoPlanet (REX)**
***Compared to REX, AEX features:***

✔ More star systems  *(Expanding not only in number, but also in scientific realism.)*

✔ More accurate red dwarf environments
*For example:
In REX (2020), all TRAPPIST-1 planets had atmospheres, which is highly unrealistic.
AEX corrects this — each body reflects current scientific understanding.*

✔ Updated data based on the newest discoveries *（All planetary parameters reference the latest publicly available research.）*

✔ Extended exploration range
- REX (2020): ~40 light-years
- AEX (2025): ~**150 light-years**

Almost four times the radius — exponentially more systems to explore.




## **_Real Exoplanet star systems already included in After-ExoPlanet:_**
- Alpha Centauri
- Barnard's Star
- Epsilon Eridani
- Tau Cet
- Teegarden's Star
- Gliese 581
- Trappist-1
- K2-18

 ## _**Known Limitations**_
Due to KSP’s floating origin and precision issues, you may encounter graphical artifacts such as:
- “cracked” terrain
- surface “mosaic” glitches
- or physics instability

These effects become more common when you travel several light-years away from the original solar system.
 ***Tip: If you use the in-game console to teleport a vessel directly to a distant star system,
these issues will almost certainly occur.
To minimize them, first teleport your craft into a high, stable orbit around the target Body,
then manually descend to the surface.***

***
# _Compatibility and  Mod Installation:_
<img width="2500" height="862" alt="awa" src="https://github.com/user-attachments/assets/dcc9d564-526b-4fbf-a11e-95930010caae" />

## **AfterSolarSystemExpand is compatible with (or provides support for) the following mods：**

- Scatterer
- EnvironmentalVisualEnhancements
- Distant Object Enhancement
- PlanetShine
- ParallaxContinued

## **AfterSolarSystem is not compatible with the following mods：**

- Principia
- RealExpand

***
# _**Installation:**_
<img width="1600" height="800" alt="Trappist-1" src="https://github.com/user-attachments/assets/c94bc228-299b-44e0-b0a9-e022e9095ab4" />

### **_Requirements:_**

- [Kopernicus](https://github.com/Kopernicus/Kopernicus/releases)

 *↑ Download the files above and unzip them, then copy them into [KSP_Root]/GameData*
  
## **_before opening the game:_**
Please make sure that Principia is **not** installed in your GameData directory！

## **_Installation method under RealSolarSystem：_**

- No.1 The AfterExpand installation package already includes a RealSolarSystem installation patch. You can simply drag it along with AfterExpand mod into GameData to replace the original mod.
- NO.2 The second method is to manually open the ```GameData/RealSolarSystem/```directory, find ```RSSKopernicusSettings.cfg```, open it with Notepad, find       ```!Body,* {} ```
in the text and replace it with
```
    !Body[Sun] {}  	  
	!Body[Moho] {}   
	!Body[Eve] {}     
	!Body[Gilly] {}
	!Body[Kerbin] {}    
	!Body[Mun] {}   
	!Body[Minmus] {} 
	!Body[Duna] {} 
	!Body[Ike] {} 
	!Body[Dres] {}  
	!Body[Jool] {}   
	!Body[Laythe] {}   
	!Body[Vall] {}   
	!Body[Tylo] {}   
	!Body[Bop] {}   
	!Body[Pol] {}   
	!Body[Eeloo] {}
```
and save it.


***

# _Contact or learn more:_
<img width="1920" height="871" alt="K2-18c" src="https://github.com/user-attachments/assets/b49bbe1a-ce4a-441f-96a8-9cc3bde260c5" />

## _**Your thoughts and suggestions**_

What if you find that there is no star system you like in After-Exoplanet, but you want to have it? No problem, feel free to suggest it to me. I will consider adding it to the game based on its system size, distance from the solar system, and other special characteristics.  Additionally, if you find any discrepancies between the current Exoplanet data and the latest scientific data, you can raise them, and I will consider making scientific corrections.
***



