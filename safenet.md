Procedimento para atualização do Safenet de 9.0 para 10.0

No terminal coloca o comando: dpkg --get-selections| grep safenet

Depois: apt-get --purge remove safenetauthenticationclient

Realiza a instalação do pacote .deb dpkg -i SafenetAuthenticationClient-10.0.37-0_amd64.deb (smb://pdnfs04/cti%20-%20utilitarios/1-ASSINADORES%20E%20TOKENS/SafeNet%205110%20-%20VALID/LINUX)
