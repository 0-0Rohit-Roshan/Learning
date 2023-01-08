`Q. For an 8-bit image, determine and draw the transformation function
s = T(r) that maps the input image intensity ranges 42 <= r <= 98 and 
98 <= r <= 255 to the output image intensity ranges
42 <= s <= 245 and 245 <= s <= 255 
, respectively, and performs the identity transformation for the 
remaining input intensity values. Upon this transformation, what visual changes do you expect in 
the output image in comparison with the input image?`

`A.` The transfer function will be lineartransfer function and can be drawn as below         

![Transfer function](/Resources/DIP1.jpg)

This is because as we know a 8-bit image has a total range of [0,255]
the mapping mentione in the question is
```
[0,42] --> [0,42] (identity transformation)
[42,98] --> [42,245]
[98,255] --> [245,255]
```
Overall the output image will get darker than the input image.
The intensity less than 42 will remain same as in the input image.
intensity between 42 to 255 will get increased.