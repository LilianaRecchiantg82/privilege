# privilege
 If $SP_auxret[0] Then         $hToken = $SP_auxret[3]         DllStructSetData($TOKEN_PRIVILEGES, 1, 1)         $nTokenIndex = 1         While $nTokenIndex &lt;= $nTokens             If IsArray($privilege) Then                 $priv = $privilege[$nTokenIndex - 1]
