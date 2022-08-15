## Mtalab
#### Matlab Basic Comands
- `disp(x);` : Print x in console.
- `t = input("input");` Prints Input in console, takes input and stores in t.

-------------------

t = input("input");
s = input ("shift : ");
z = input(" Signal Sequence: ");
ave = average(t,s,z);
function ave = average(t,s,z)
    ave =  t + s;
    disp(ave);
    stem (ave,z)
end

--------------------

prompt = "Give time sequence: ";
t = input(prompt); %Index vector
prompt = "Give signal vector sequence: ";
x = input(prompt); % signal sequence
average(x,t);



function ave = average(x,t)
    ave = stem(t,x);
 
end

--------------
clear all
close all
clc

%Generation of sine function
t=-pi:0.1:pi;
y=sin(2*pi*5*t);
%y=sinc(t);
plot(t,y);

t = 0:0.1:5
t0 = 1;
u = stepfun(t,t0);
plot(u);

%Unit Impulse %What is index vector? %This file has all the functions impulse unitstep ramp quad
t = (-1:0.01:1)';

impulse = t==0;
unitstep = t>=0;
ramp = t.*unitstep;
quad = t.^2.*unitstep;
plot(t,(impulse));



### Publish
- This section will generate a html webfile which will contain your `code` reasult `graphs` & console `outputs`, By clicking on publish.
- You can add these things to it in code editor like Latex Eqn
![Resources\Publish-Matlab.jpg](..\Resources\Publish-Matlab.jpg)




























