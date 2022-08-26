# taller-26-de-agosto
´´´´

    Sub actividad()
     
    ingresos = InputBox("ingrese impuestos anuales de la empresa")
    
    If ingresos >= 0 And ingresos < 1000 Then
        MsgBox "no paga impuesto"
    Else
        If ingresos >= 1001 And ingresos < 10000 Then
            valor = 0.05 * ingresos
            MsgBox "el impuesto a pagar anual es:" & valor
            Else
            If ingresos >= 10001 And ingresos < 100000 Then
                valor = 0.1 * ingresos
                MsgBox "el impuesto a pagar anual es:" & valor
            Else
                If ingresos >= 100001 And ingresos < 1000000 Then
                    valor = 0.15 * ingresos
                    MsgBox " el impuesto a pagar es:" & valor
                Else
                    If ingresos >= 1000001 And ingresos < 10000000 Then
                    valor = 0.2 * ingresos
                    MsgBox " el impuesto a pagar es:" & valor
                    Else
                    If ingresos >= 10000001 Then
                        valor = 0.25 * ingresos
                        MsgBox "el impuesto a pagar es:" & valor
                    Else
                        MsgBox "No se puede"
                    End If
                    End If
                End If
            End If
        End If
    End If
    End Sub
´´´´