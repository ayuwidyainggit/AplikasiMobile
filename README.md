
# AYU WIDYA INGGIT

Login.php
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="">
    <meta name="author" content="Dashboard">
    <meta name="keyword" content="Dashboard, Bootstrap, Admin, Template, Theme, Responsive, Fluid, Retina">

    <title>DASHGUM - Bootstrap Admin Template</title>

    <!-- Bootstrap core CSS -->
    <link href="assets/css/bootstrap.css" rel="stylesheet">
    <!--external css-->
    <link href="assets/font-awesome/css/font-awesome.css" rel="stylesheet" />
        
    <!-- Custom styles for this template -->
    <link href="assets/css/style.css" rel="stylesheet">
    <link href="assets/css/style-responsive.css" rel="stylesheet">

    <!-- HTML5 shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
      <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>


# ANALISIS:

1. pada menu login, sudah responsive karena sudah ada <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
2. terdapat initial-scale=1.0 jadi user diijinkan untuk melakukan zoom out atau zoom in.
3. Tag ini berada pada baris ke 5.
4. Login.php ini berada pada folder proyekmobile\user\login.php
5. Aplikasi ini menggunaan bootstrap
6. Aplikasi ini menggunakan html5

## index.html

<head>
    <meta charset="utf-8" />
    <link rel="apple-touch-icon" sizes="76x76" href="../assets/img/apple-icon.png" />
    <link rel="icon" type="image/png" href="../assets/img/favicon.png" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
    <title>CV Akakom 1</title>
    <meta content='width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0' name='viewport' />
    <meta name="viewport" content="width=device-width" />
    <!-- Bootstrap core CSS     -->
    <link href="../assets/css/bootstrap.min.css" rel="stylesheet" />
    <!--  Material Dashboard CSS    -->
    <link href="../assets/css/material-dashboard.css?v=1.2.0" rel="stylesheet" />
    <!--  CSS for Demo Purpose, don't include it in your project     -->
    <link href="../assets/css/demo.css" rel="stylesheet" />
    <!--     Fonts and icons     -->
    <link href="http://maxcdn.bootstrapcdn.com/font-awesome/latest/css/font-awesome.min.css" rel="stylesheet">
    <link href='http://fonts.googleapis.com/css?family=Roboto:400,700,300|Material+Icons' rel='stylesheet' type='text/css'>
</head>

Pada halaman ini belum responsif karena <meta name="viewport" content="width=device-width, initial-scale=1.0"> namun hanya terdapat     <meta name="viewport" content="width=device-width" /> dan ketika dibuktikan dengan inspect, masih terdapat menu yang belum tampil ketika diakses dengan smart phone.
Untuk tampilannya diperindah dengan menggunakan     <link href="http://maxcdn.bootstrapcdn.com/font-awesome/latest/css/font-awesome.min.css" rel="stylesheet">


## Css :

* {
	margin: 0px; 
	padding: 0px; 
	box-sizing: border-box;
}

body, html {
	height: 100%;
	font-family: Poppins-Regular, sans-serif;
}

/*---------------------------------------------*/
a {
	font-family: Poppins-Regular;
	font-size: 14px;
	line-height: 1.7;
	color: #666666;
	margin: 0px;
	transition: all 0.4s;
	-webkit-transition: all 0.4s;
  -o-transition: all 0.4s;
  -moz-transition: all 0.4s;
}

Untuk margin, padding,  menggunakan px, 
Height menggunakan 100% 
Transition menggunakan s 
 

