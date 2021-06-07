Landing Page
HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dear Dessert - Home</title>
    <link rel="stylesheet" href="Landingpage.css">
</head>
<body>
    <div class="customer">
        <a href="http://www.baidu.com">Sign Up</a>
        <a href="http://www.google.ca">View Cart</a>
    </div>

    <header>
        <img src="images/logo.png" width=50px/>
        <h1>Welcome to Dear Dessert</h1> 
        <p>We are a well-known dessert chain located in the Ottawa area. <br>
            We were established in 2000 and have 10 branches in Ottawa. <br>
            Our products mainly include cakes, breads and biscuits, etc. <br>
            You are welcome to buy.
        </p>
        <div>
            <input type="text" value="Cupcake">
            <a href="Resultpage.html"><input type="button" value="Search"></a>
        </div> 
    </header> 
   
    <section>
        <nav>
            <ul>
                <li><a href="#">Breads</a></li>
                <li><a href="#">Cakes</a></li>
                <li><a href="#">Cookies</a></li>
            </ul>
        </nav>
        <table>
            <tr>
                <td><img src="images/RaisinBread.jpg" height=200px width=300px></td>
                <td colspan="2"><p>Under the bread category, our specialty product is raisin bread.
                    We use blackcurrant raisins. The taste is sweet and sour, and the juice is rich. 
                    It can perfectly blend with the taste of bread.</p></td>
            </tr>
            <tr>
                <td colspan="2"><p>Under the cake category, our specialty product is chocolate cake. 
                    We use pure cocoa to make the most delicious chocolate cake. 
                    In addition, the sweetness of the chocolate cake is optional, and we can use sugar-free cocoa.</p></td>
                <td><img src="images/ChocolateCake.jpg" height=200px width=300px></td>

            </tr>
            <tr>
                <td><img src="images/Candy Cookies.jpg" height=200px width=300px></td>
                <td colspan="2"><p>Under the category of biscuits, our specialty product is candy cookies.
                    This kind of biscuit has colorful candies on top of the delicious biscuit, which looks very attractive.
                    Candies can be customized according to your needs.</p></td>
            </tr>
        </table>
        
        
      </section>

</body>
</html>
