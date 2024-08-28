<h1>Checklist - Instalação do VMWare vSphere, Criação da Máquina Virtual e Boot do Linux na Versão Debian12 - 2/2024.</h1>

> 📍 FATEC - Registro.

### 📃 Sumário.
> 👨🏽‍💻 Instalação do VMWare vSphere 6.0.

> 💿 Configuração para criar a imagem de disco.

> 🌐 Configuração da distribuição da imagem criada utilizando o método baseado em REDE.

#

### 👨🏽‍💻 Configuração inicial para a instalação do VMWare vSphere.
> ⚠️ Neste primeiro momento você vai alterar a compatibilidade do instalador para que o mesmo inicie sem nenhum tipo de erro por versionamento.
  
  + ⚙️ Identifique o instalador do VMWare vSphere.
    + 🔧 ![image](https://github.com/user-attachments/assets/14624843-eebe-4579-9263-4aa3db4edb21)

  + ⚙️ Clique com o botão direito e vá até a opção "Propriedades" e em seguida vá até a aba "Compatibilidade", defina a compatibilidade para "Windows 7".
    + 🔧![image](https://github.com/user-attachments/assets/2aa2ba20-4c5d-4bff-863c-28d5cdb91b5b)

  + ⚙️ Aguarde a extração.
      + 🔧![image](https://github.com/user-attachments/assets/6a1f8922-64db-4c3c-84c0-0636c8b4cf0d)
        
  + ⚙️ Selecione o idioma.
      + 🔧![image](https://github.com/user-attachments/assets/076d62aa-53a6-425b-b26d-f06fac54891b)
        
  + ⚙️ Selecione a opção "Next".
      + 🔧![image](https://github.com/user-attachments/assets/90f87562-c85a-4aa5-b554-469a403decd3)
        
  + ⚙️ Aceite os termos.
      + 🔧![image](https://github.com/user-attachments/assets/ae65865e-44a7-40ec-bd26-820d47ad6b01)

### 👨🏽‍💻 Criando a Máquina Virtual no VMWare vSphere.
> ⚠️ Neste momento seguiremos para a criação da máquina virtual, é importante prestar atenção a cada passo, pois são processos que irão determinar o funcionamento correto da sua máquina virtual.

  + ⚙️ Para iniciar a criação da VM, clique em "Inventory".
      + 🔧![image](https://github.com/user-attachments/assets/4c95e7c5-f316-4b83-9ac5-cf47135eeae9)
        
  + ⚙️ Clique em "New Virtual Machine".
      + 🔧![image](https://github.com/user-attachments/assets/ab5b87e0-a6ff-45f0-b0d5-b40960198de9)
        
  + ⚙️ Selecione a opção "Typical".
      + 🔧![image](https://github.com/user-attachments/assets/f0198453-6108-4064-b00c-a2a46becb4cd)
        
  + ⚙️ Insira o nome da equipe no formato padrão "cloud-dsm*-ambiente-sistemaoperacional".
      + 🔧![image](https://github.com/user-attachments/assets/0d8b16a8-51a8-45c1-8e9c-c030a6f5f020)

  + ⚙️ Defina o "Datastore" disponível para armazenamento.
      + 🔧![image](https://github.com/user-attachments/assets/2a3d539f-5e2b-4def-ba29-82bf1492a150)

  + ⚙️ Selecione a seguinte versão do Debian.
      + 🔧![image](https://github.com/user-attachments/assets/3a1a0a9e-df83-4309-8f68-1522bd44190d)

  + ⚙️ Clique em "Next" nesse momento.
      + 🔧![image](https://github.com/user-attachments/assets/5bcdbb8d-9038-4ab5-b58f-6d1bc41d4d03)

  + ⚙️ Defina a quantidade de armazenamento que será utilizado na VM.
      + 🔧![image](https://github.com/user-attachments/assets/d6300214-94ab-49c1-b654-256b26776a2b)

  + ⚙️ Por fim, clique em "Finish" para concluir a criação da VM.
      + 🔧![image](https://github.com/user-attachments/assets/4bf14376-8578-41ee-b8af-43a1fffee694)

  + ⚙️ 
      + 🔧
