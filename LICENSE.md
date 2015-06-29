
Sub Main()

        Dim St, Np, No, Nc As Double

        Console.WriteLine("Digite Superficie del Terreno En m² : ")
        St = Console.ReadLine()
        If St <= 1000000 Then
            Np = ((St * 0.5) \ 10) * 8
            No = ((St * 0.3) \ 15) * 15
            Nc = ((St * 0.2) \ 18) * 10
        Else
            Np = ((St * 0.7) \ 10) * 8
            No = ((St * 0.2) \ 15) * 15
            Nc = ((St * 0.1) \ 18) * 10

        End If
        Console.WriteLine("# De Pinos : " & Np)
        Console.WriteLine("# oyamel   : " & No)
        Console.WriteLine("# cedro    : " & Nc)
        Console.ReadLine()

    End Sub

End Module
