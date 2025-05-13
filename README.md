function Estnumerocamerounais(As string)bolean
    Dim pattern As string="^(\
+237|00237)?[6-9][0-9]{8}$"
    Dim regex As New
regex(pattern)
    return regex.IsMatch(numéro)
 End function   
