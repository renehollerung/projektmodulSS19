<template> 
    <div> 
      
        <h1 align= "center"> Feedback System</h1>
        <hr/>
    
    <body>
        <br>
        <br>
        <br>
        <br>
            <form name="registerForm" method="post" action="register.php">
                    <table width="20%"  align="center">
                    
                    <tr>
                    <td colspan=2><center><font size=4><b>Registrierung</b></font></center></td>
                    </tr>
                    
                    <tr>
                    <td>Benutzername:</td>
                    <td><input type="text" size=25 name="userid"></td>
                    </tr>
                        
                    <tr>
                    <td>WHZ-Email:</td>
                    <td><input type="email" size=25 name="email"></td>
                    </tr>

                    <tr>
                    <td>Passwort:</td>
                    <td><input type="Password" size=25 name="pwd"></td>
                    </tr>

                    <tr>
                    <td>Passwort wiederholen:</td>
                    <td><input type="Password" size=25 name="pwd_repeat"></td>
                    </tr>
                    
                    <tr>
                    <td><input type="checkbox" size=25 name="checkbox"></td>
                    <td>Ich stimme den AGBs zu.</td>
                    </tr>

                    <tr>
                    <td></td>
                    <td><input type="submit" value="Register"></td>
                    </tr>
                    
                    </table>
                    </form>
    </body>
    </div>
</template>

<script>
 
</script>

<style>

</style>