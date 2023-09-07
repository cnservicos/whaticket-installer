ferramenta interativa para instalar e atualizar o whaticket automático
### download & setup

Primeiro você precisa baixá-lo:


```bash
sudo apt -y update && apt -y upgrade
sudo apt install -y git
git clone https://github.com/cnservicos/whaticket-installer.git
```

Agora, tudo que você precisa fazer é torná-lo executável:

```bash
sudo chmod +x ./whaticket-installer/whaticket
```

### usage

Depois de baixá-lo e torná-lo executável, você precisa **navegar até** o diretório do instalador e **executar o script com sudo**:
```bash
cd ./whaticket-installer
```

```bash
sudo ./whaticket
```
