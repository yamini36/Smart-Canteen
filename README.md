CODE FOR HOME PAGE:
<html>
<head>
<style type='text/css' rel="stylesheet">
.p{
  background-color:yellow;
   color:green;
}
</style>
</head>
<body>
<form>
<table align="center" style="width:50%" border='4'>
<tr>
<td colspan='4' align="center" class="p" style="font-size:60px;">SMART CANTEEN</td>
<td><img src="C:\Users\niharika\Desktop\pictures-for-project\canteenlogo.png" length=150 width=150></td>
</tr>
<tr><td colspan='2'><marquee direction='right'>Canteen opens from 8:00AM to 8:00PM</marquee>
<p align="center">ENJOY YOUR DAY</p>
</td></tr>
<tr><td><a href="home.html">Home</a></td></tr>
<tr><td><a href="items.html">Items</a></td></tr>
<tr><td><a href="offers.html">Offers</a></td></tr>
<tr><td><a href="contactus.html">Contact us</a></td></tr>
<tr><td><a href="aboutus.html">About us</a></td></tr>
</tr>
</table>
</form>
</body>
</html>


CODE FOR ITEMS PAGE:
<html>
<head>
<title>Canteen2</title>
<style>
.links
{
border-radius:10px;
}
.links:hover
{
background-color:pink;
}
</style>
</head>
<body>
<table border="0" width="100%" height="10%">
<tr>
<td width="12.5%" align="center" bgcolor="skyblue" class="links"><font color="white">HOME</td>
<td width="12.5%" align="center" bgcolor="skyblue" class="links"><font color="white"><a href="items.html">ITEMS</td>
<td width="12.5%" align="center" bgcolor="skyblue" class="links"><font color="white"><a href="offers.html">OFFERS</a></td>
<td width="12.5%" align="center" bgcolor="skyblue" class="links"><font color="white"><a href="contactus.html">CONTACT US</td>
<td width="12.5%" align="center" bgcolor="skyblue" class="links"><font color="white"><a href="aboutus.html">ABOUT US</td>
<td width="12.5%" align="center" bgcolor="skyblue" class="links"><font color="white"><a href="menu.html">MENU</td>
<td width="12.5%" align="center" bgcolor="skyblue" class="links"><font color="white"><a href="feedback.html">FEEDBACK</td>
</tr>
</table>

<h1 style=font-size:"100px"><marquee>Welcome To Smart Canteen</marquee></h1>
<h2 align="center">Start Your Day With Healthy Food</h1>

<h1>ITEMS1</h1>
<p><img src="images\collage1.jpg" width="50%"></p>
<p><a href="tiffins.html">tiffins</a></p>
<p><img src="images\collage6.jpg" width="50%"></p>
<p><a href="cooldrinks.html">cooldrinks</a></p>
<p><img src="images\collage4.jpg" width="50%"></p>
<p><a href="Fast-foods.html">Fast-foods</a></p>
<p><img src="images\collage5.jpg" width="50%"></p>
<p><a href="Snacks.html">Snacks</a></p>
<p><img src="images\collage2.jpg" width="50%"></p>
<p><a href="Juices.html">Juices</a></p>
<p><img src="images\collage3.jpg" width="50%"></p>
<p><a href="Chocolates.html">Chocolates</a></p>
</head>
</body>


CODE FOR JAVA SERVER PAGE:

Import java.io.IOException;
import java.io.PrintWriter;
import java.sql.Connection;
import java.sql.PreparedStatement;

import javax.servlet.ServletException;
import javax.servlet.annotation.WebServlet;
import javax.servlet.http.HttpServlet;
import javax.servlet.http.HttpServletRequest;
import javax.servlet.http.HttpServletResponse;

import smartcafe.Jdbc;



/**
 * Servlet implementation class customerreg
 */
@WebServlet("/customerreg")
public class customerreg   extends HttpServlet {
	private static final long serialVersionUID = 1L;
       
    /**
     * @see HttpServlet#HttpServlet()
     */
    public customerreg() {
        super();
        // TODO Auto-generated constructor stub
    }

	/**
	 * @see HttpServlet#doGet(HttpServletRequest request, HttpSe…



