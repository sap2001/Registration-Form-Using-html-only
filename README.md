# Registration-Form-Using-html-only
form.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
</head>
<body>
    <h1 style="text-align: center;"  >Registraion form in html</h1>
    <form>
        <table>
            <tr>
               <td>
                Name:
               </td>
            
            <td>
                <input type="text" placeholder="Name" name="">
           
            </td>
        </tr>
        <tr>
            <td>
                Mobile:
            </td>
            <td>
                <input type="phone" placeholder="967********">
            </td>
        </tr>

        <tr>
            <td>Email id:</td>
            <td>
                <input type="email" placeholder="xyz@gmai.com">
            </td>
        </tr>
        <tr>
            <td>Password:</td>
            <td>
                <input type="password" placeholder="password">
            </td>
        </tr>
        <tr>
            <td>Gender:</td>
            <td>
                <input type="radio" name ="Gender">Male
                <input type="radio" name="Gender">Female
            </td>
        </tr>
        <tr>
            <td>DOB:</td>
            <TD>
                <input type ="date" name="DOB">
            </TD>
            </tr>
            <tr>
                <td>city</td>
                <td>
                    <input type="checkbox" Pune>Pune
                    <input type="checkbox" Mumbai>Mumbai
                    <input type="checkbox" Dellhi>Dellhi
                </td>
            </tr>
            <tr>
                <td>Education:</td>
                <td>
                    <select>
                        <option>10+2</option>
                        <option>Graduation</option>
                        <option>PostGraduation</option>
                        <option>Select Option</option>
                    </select>
                </td>
            </tr>

            <tr>
                <td>Graduation Name:</td>
                <td>
                    <select>
                        <option>Select Option</option>
                        <option>BE/B.Tech</option>
                        <option>B.COM/M.COM</option>
                        <OPTION>BA./MA</OPTION>
                        <OPTION>B.Pharm/M.Pharm</OPTION>
                    </select>
                </td>
            </tr>

            <tr>
                <td>Address</td>
                <td>
                    <textarea rows ="4" col="10" placeholder="Address"></textarea>
                </td>
            </tr>

            <tr>
                <td>
                    <input type="Submit" value="Submit">
                    <input type="Reset" value ="Reset">
                </td>
            </tr>
        </table>
    </form>
    
</body>
</html>
