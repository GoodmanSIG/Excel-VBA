Function prodej(hodnota As Double) As Double

    Dim procento1 As Double
    Dim procento2 As Double
    procento1 = Range("A1").Valu
    procento2 = Range("A2").Value

    Dim slevy As Double
    slevy = hodnota * (procento1 / 100) + hodnota * (procento2 / 100)
    prodej = hodnota - slevy
End Function

