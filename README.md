## Project-RC

This project is aimed to find the following details from given RC card:

1> License plate number
2> VIN number
3> Name
4> Engine number
5> Registration date
6> Manufacturing date

Approach Used :

In this project I have used certain python modules such as pytesseract, datefinder, PIL, cv2, imutils, etc along with certain algorithms to
extract required data out of the images. Approaches used are -

    a) License plate number : Used the common keywords present before license plate numbers then extracted required data from it.
    b) VIN number           : Used regex module of python to check possible strings for VIN number, then used length of VIN number as a 
                              property to find VIN number.
    c) Name                 : Used regex module to extract possible name from the text.
    d) Engine number        : Used regex and keywords to identify engine number.
    e) Registration date    : Used keywords to identify registration date, then used datefinder module of python to find dates.
    f) Manufacturing date   : Used keywords to identify manufacturing date, then used datefinder module of python to find dates.
