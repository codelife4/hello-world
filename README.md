# hello-world
it's about my vb.net coding which is freaking me out for 2 hours by reason of not working. (no syntax problem, its just logical and im new on vb.net, help me out improve vb.net)
Public Class Form1
    Private Sub Form1_Load(sender As Object, e As EventArgs) Handles MyBase.Load

    End Sub

    Private Sub Button1_Click(sender As Object, e As EventArgs) Handles Button1.Click

        If TextBox1.Text = "" Then
            MsgBox("basma demiştim")
            Button1.BackColor = Color.Red
            MsgBox("bilgisayarın ele geçirildi")
        End If
        Dim yas As Integer
        TextBox1.Text = yas
        If (yas < 18) Then
            MsgBox("18 yaşından kücükler giremez")
            MsgBox("büyü de gel")
        End If
        If (yas > 18) Then

            Button1.BackColor = Color.GreenYellow
            MsgBox("partiye hosgeldiniz")
            MsgBox("iyi eğlenceler")
        End If
    End Sub
End Class
