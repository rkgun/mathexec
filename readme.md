# What is Math Exec?

Math Exec is an html document that uses js and jquery in the background and is used to perform mathematical operations.

I used the Katex library to display mathematical expressions in latex form, and the Tailwind library for elements to have a neat appearance. Mathjs, which uses the Hunting Yards algorithm, does the mathematical operations.

Before starting use:
Open the "mathexec" folder and enter the code below

    npm install

After the necessary node packages are installed, open the index.html page in a web browser.

Enter the expression you want to calculate in the black box. Some supported syntaxes include:

- 3+5
- sqrt(3)
- sin(45 deg)
- 12.7 cm to inch
- derivative('x^2 + x', 'x')
- f(a,b)=a+b;a=2;b=3;f(a,b)

etc... A list of some supported expressions is available in the fncs.md file.

Library links:

 - [Tailwind](https://tailwindcss.com/)
 - [MathJs](https://mathjs.org/)
 - [Katex](https://katex.org/)
