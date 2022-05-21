# CustomName
AutoItSetOption ( "MustDeclareVars", 1) myFunction()   Func myFunction($getCustomName=True)     If $getCustomName Then         MsgBox(0,"Custom Name",$getCustomName)     Else         MsgBox(0,"Custom Name","None Given")     EndIf EndFunc
