### Overview ###
This project includes all the source files to accompany a forthcoming tutorial for re-creating Space Invaders using an object oriented approach with Actionscript 3.0 in Flash.

Classes include;
| SpaceInvaders.as | Document class |
|:-----------------|:---------------|
| Invader.as       | An individual invader |
| Player.as        | The defender   |
| Spaceship.as     | Flying saucer from top of screen |
| Defence.as       | An individual barrier |
| InvaderBullet.as | Bullet fired by an invader |

### Movement ###
Much of the movement within the game is created by combinig AS3 Timer events with coded tweens (using the popular [TweenMax](http://www.greensock.com/tweenmax/) library). You will need to place the TweenMax library files into your Flash includes directory to successfully compile the program from the source .fla file within Flash. For more information about TweenMax, including documentation, tutorials and to download the tweening library files see the [Greensock TweenMax site](http://www.greensock.com/tweenmax/).


### Design ###
The design of the screen layout was based upon the following raw screenshot derived from the original 1978 arcade version of Space Invaders. The following black and white image does not feature the arcade background or colour overlay...

---

![http://www.old-computers.com/museum/software/arcade_space-invaders_s1.png](http://www.old-computers.com/museum/software/arcade_space-invaders_s1.png)

---

![http://www.old-computers.com/museum/software/arcade_space-invaders_cabinet_m.jpg](http://www.old-computers.com/museum/software/arcade_space-invaders_cabinet_m.jpg)

---

Images from: [www.old-computers.com](http://www.old-computers.com/museum/software_detail.asp?st=1&c=&id=72)
