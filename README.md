# 👨‍💻 PAINELWEB GESTOR-SSH SWIT-T
⚠ SISTEMAS SUPORTADOS: (DEBIAN 8, UBUNTU 14 E UBUNTU 18!).⚠ </br>
⚠  VPS RECOMENDADA PARA PAINEL WEB: https://www.avirahost.com.br/aff.php?aff=108 ⚠
```
apt update -y; apt upgrade -y; apt install wget -y; bash <(wget -qO- https://github.com/JeanRocha91x/psshplus-/raw/main/gestorssh/instpainel.sh)
```

# ♻ SINCRONIZAR NA VPS SSH!
```
apt install wget -y; bash <(wget -qO- https://github.com/JeanRocha91x/psshplus-/raw/main/gestorssh/sincpainel.sh)
```

# 🛂 CHECKUSER PARA O APP CONECTA4G!
```
apt install wget -y; bash <(wget -qO- https://github.com/JeanRocha91x/psshplus-/raw/main/gestorssh/instcheck.sh)
```

# ✅ ATUALIZAÇÃO 29/08/2022
```
1- Comando pweb
(Funciona via terminal SSH)

2- Painel Conecta4G 
(Usuário/Senha: admin/admin)

3- Loja de APPS 
(Link na tela de login/Revenda e Login/Admin)
(Troca de cor da Top-Bar e icones nos Textos)

4- Background Área Revenda e Área Admin
(Para alterar as imagens, basta trocar as images na pasta /var/www/html/app-assets/images/background/)
(Manter os mesmos nomes nas imagens novas (bk-admin.jpg = para admin) e (bk-rv.jpg = para revenda))

5- Texto Flutuante na Tela Login/Revenda
(📣 NOVIDADES AQUI !!!) Para editar, basta ir em /var/www/html/index.php (linha 86)

6- Página de Termos de Uso editada
(foi adicionado uma imagem no topo)
(cor do background trocada)

7- Todos os nomes GESTOR-SSH foi trocado por EMPRESA
(quando alterar o NOME DA LOGO no painel pweb, Todos os texto EMPRESA será trocado também.)
```
