<img width="136" height="36" alt="image" src="https://github.com/user-attachments/assets/11ec654f-f2a9-4e24-bc45-cecb21d4889f" /># Xampp_portable
Precisa programar para web sem acesso de administrador? Tenho a solução! Com o Xampp portable é possível usar os componentes sem acesso administrador no computador.
Apache, Mysql, Tomcat... 
Como usar o XAMPP:
## 1º Passo: Ao baixar o arquivo, extraia a pasta zip;
## 2º Passo: Se ele tiver criado uma pasta XAMPP, mova ela para o dico C:
## 3ª Passo: Inicie o arquivo "XamppControl" <img width="136" height="36" alt="image" src="https://github.com/user-attachments/assets/0e46d822-b71a-48e4-b5f5-13698e1c0eb2" />



# OBS: Caso ocorra o erro de ele não iniciar o apache ou o mysql é devido a um conflito de porta de serviço. Basta somente alterar a porta ele funciona normalmente.
## Para alterar a porta do apache, acesse em config/Apache Httpd.conf <img width="405" height="73" alt="image" src="https://github.com/user-attachments/assets/b4f4d244-94d2-43f1-bee6-e7fdb4e9516a" /> e busque por Listen e altere o valor para 8080, ele estará na porta padrão 80, além disto você deve acessar o "config" padrão do xampp e depois a opção "Service and Port Settings" <img width="835" height="634" alt="image" src="https://github.com/user-attachments/assets/39a76fa3-1716-45e0-97e6-92dc1642eee4" /> e busque pela opção do apache e alterar a porta pela que colocou em listen no arquivo Apache Httpd.conf.
## Para a porta do Mysql é a mesma ideia, vá na opção "config" do Mysql, abra o arquivo my.ini <img width="680" height="90" alt="image" src="https://github.com/user-attachments/assets/51e8987f-ba39-4097-9e7e-85283563ac29" /> e altere a "port" estará padrão com "port=3306" mude para "port=3307". Vá também em "config" padrão do xampp e depois a opção "Service and Port Settings" <img width="1229" height="640" alt="image" src="https://github.com/user-attachments/assets/c9644298-bec5-47e7-9215-cf0342236756" /> e busque pela opção do mysql e coloque a porta "3307" também.

