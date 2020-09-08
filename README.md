# config
    * Keyboard
        1.Download colemak (https://colemak.com/)

        2.modify reg
            * reg path  =  HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\
            * win10 modify  00000804>Layout File value=Colemak2.dll
        3.Import etc-tab-alt-crl.reg
            * esc ⇌ tab
            * alt ⇌ crl (Left)

    * Microsoft pinyin add 小鹤双拼
        * reg path  =  \HKEY_CURRENT_USER\Software\Microsoft\InputMethod\Settings\CHS
        1.add str name  =   UserDefinedDoublePinyinScheme0
        2.str value     =   小鹤双拼*2*^*iuvdjhcwfg^xmlnpbksqszxkrltvyovt
        3.modify Microsoft pinyin programme
        
