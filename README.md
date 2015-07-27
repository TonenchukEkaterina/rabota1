# rabota1
<!DOCTYPE HTML> 
3	<html> 
4	<head> 
5	<title>Лабораторная 1</title> 
6	</head> 
7	<body>
8	<script> 
9	var a;
10	var b;
11	var c;
12	var chislo1 = prompt('Введите a', ''); 
13	var chislo2 = prompt('Введите b', ''); 
14	var chislo3 = prompt('Введите c', ''); 
15	a= parseInt(chislo1);
16	b= parseInt(chislo2);
17	c= parseInt(chislo3);
18	var a2 = Math.pow(a,2);
19	var b2 = Math.pow(b,2);
20	var c2 = Math.pow(c,2);
21	if  (a + b > c && a + c > b && b + c > a && a > 0 && b>0 && c>0 ) 
22	{ 
23	document.write("Треугольник существует" + "<br>" );
24	if (a2 < b2 + c2 && b2 < a2 + c2 && c2 < a2 + b2)
25	{
26	document.write("Треугольник остроугольный" + "<br>" );
27	}
28	else 
29	{
30	document.write("Треугольник прямоугольный или тупоугольный" + "<br>" );
31	}
32	}
33	else
34	{
35	document.write("Треугольник не существует" + "<br>" );
36	}
37	</script>
38	</body> 
39	</html> 
