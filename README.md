# bigip_autenticacao_tacacs
Configuração de autenticação no Bigip via TACACs com remote-role.

Nesse repositório vou demonstrar como configurar o Bigip para fazer autenticação via TACACs, mantendo os níveis de permissão e partições definidas nas configurações de "remote-roles" do Bigip.

Serão abordadas as configurações tanto do TACACs (utilizaremos um servidor Linux Ubuntu), como as configurações do Bigip, serão utilizados como base para as configurações os artigos abaixo:

https://devcentral.f5.com/s/articles/v10-remote-authorization-via-tacacs-43

https://devcentral.f5.com/s/articles/tacacs-remote-role-configuration-for-big-ip

