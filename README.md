# JackySiek-01082170040
Weekly submission for lab AA TIF UPH 2018/2019 by Livia Lohanda

912A-Tricky Alchemy

The Problem of Tricky Alchemy are, how many Grisha needs the colour crystal which is have 2 colours, yellow and blue to make crystals for the amount of colour balls as he wants. Then we just have to make the calculations like this:

So from the questions given: "It's known that to produce a yellow ball one needs two yellow crystals, green — one yellow and one blue, and for a blue ball, three blue crystals are enough. if (cy<(2*y+g)) a+=((2*y+g)-cy);

so if the amount of cy (Crystal Yellow) is less than 2 Yellow + green(this is because 1 Yellow ball needs 2 crystal and 1 Green ball needs 1 yellow crystal, then i save the amount in a and the total of 2 Yellow Ball + 1 Green Ball subtract by the Crystal Yellow and added with the a. then for the second code is

if (cb<(g+3*b)) a+=((g+3*b)-cb);

this code was made for the blue crystal. both of the codes are made in purpose so that if the crystal are needed to add.
then after the code done, simply print out the "a".
