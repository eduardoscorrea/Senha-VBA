# Senha-VBA
Um “aplicativo” muito interessante para retirar senha planilha, quando uma planilha está com proteção de sheets ou de células .

Este aplicativo insere um menu em Ferramentas  para desativar proteção, ai basta abrir a planilha com bloqueios e desativar clicando no menu.

http://excelevba.com.br/retirar-senha-planilha/

Sub Desbloqueia_Planilha()
 
Dim i As Integer, j As Integer, k As Integer
Dim l As Integer, m As Integer, n As Integer
On Error Resume Next
For i = 65 To 66
For j = 65 To 66
For k = 65 To 66
For l = 65 To 66
For m = 65 To 66
For i1 = 65 To 66
For i2 = 65 To 66
For i3 = 65 To 66
For i4 = 65 To 66
For i5 = 65 To 66
For i6 = 65 To 66
For n = 32 To 126
ActiveSheet.Unprotect Chr(i) & Chr(j) & Chr(k) & _
Chr(l) & Chr(m) & Chr(i1) & Chr(i2) & Chr(i3) & _
Chr(i4) & Chr(i5) & Chr(i6) & Chr(n)
If ActiveSheet.ProtectContents = False Then
MsgBox "Sua planilha foi desbloqueada "
Exit Sub
End If
Next
Next
Next
Next
Next
Next
Next
Next
Next
Next
Next
Next
 
End Sub
