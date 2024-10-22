# PROMPT:

For years, strange signals pulsed through the air on the eve of October 31st. Some said it was the voice of an ancient witch, others believed it was a message from something far darker. A cryptic message, scattered in three parts, was intercepted by a daring group of villagers. Legend spoke of a deal made between the witch and a shadowy figure, but the true intent of their secret could only be revealed by those brave enough to decipher it before midnight, when the veil between worlds would thin.

---

# METHODS:

This challenge provides us with a crypto_sugar_free_candies.zip file.

The file consists of a folder containing two files. one named output.txt:

v1 = 4196604293528562019178729176959696479940189487937638820300425092623669070870963842968690664766177268414970591786532318240478088400508536
v2 = 11553755018372917030893247277947844502733193007054515695939193023629350385471097895533448484666684220755712537476486600303519342608532236
v3 = 14943875659428467087081841480998474044007665197104764079769879270204055794811591927815227928936527971132575961879124968229204795457570030
v4 = 6336816260107995932250378492551290960420748628

and one named source.py which is a python script.

https://docs.python.org/3.10/tutorial/appetite.html

We can use the `python3` command to attempt and execute the `source.py` script, but get the following error on our home system:

`Traceback (most recent call last):
  File "/home/seb/Documents/crypto_sugar_free_candies/source.py", line 1, in <module>
    from Crypto.Util.number import bytes_to_long
ModuleNotFoundError: No module named 'Crypto'`

