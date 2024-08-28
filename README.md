<h1>Checklist - Instalação do VMWare vSphere, Criação da Máquina Virtual e Boot do Linux na Versão Debian12 - 2/2024.</h1>

> 📍 FATEC - Registro.

### 📃 Sumário.
> 👨🏽‍💻 Instalação do VMWare vSphere 6.0.

> 💿 Criando a Máquina Virtual no VMWare vSphere.

> 🌐 Instalação do Debian 12 na Máquina Virtual.

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

### 💿 Criando a Máquina Virtual no VMWare vSphere.
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

### 🌐 Instalação do Debian 12 na Máquina Virtual.
> ⚠️ Agora que a máquina virtual já está criada, será necessário instalar a imagem do Linux Debian 12. Para isso você fará os seguintes passos.

  + ⚙️ Selecione a máquina virtual que você criou.
      + 🔧![image](https://github.com/user-attachments/assets/f4382d72-13ac-44c0-b47c-07ba7a3566d6)
        
  + ⚙️ Em seguida selecione a seguinte opção.
      + 🔧![image](https://github.com/user-attachments/assets/78f5ee55-5223-4438-949c-48ff8e0133f3)

  + ⚙️ Selecione a opção "Connect to ISO ... ".
      + 🔧![image](https://github.com/user-attachments/assets/ea509ebd-7283-4de8-ad33-e106d1a1cc32)
   
  + ⚙️ Selecione a ISO do Debian disponível no computador local.
      + 🔧![image](https://github.com/user-attachments/assets/60e5cb7e-f356-48ba-8b57-a88a305feef0)
   
  + ⚙️ Abra o console.
      + 🔧![image](https://github.com/user-attachments/assets/f0334495-e9aa-44b4-956b-6d5f3c75dc3c)

  + ⚙️ Selecione a segunda opção.
      + 🔧![image](https://github.com/user-attachments/assets/17232566-3e3b-476b-8ae9-fd5ab2722d1c)
        
  + ⚙️ Faça a seleção do idioma.
      + 🔧![image](https://github.com/user-attachments/assets/4162e590-358e-4df5-aea8-2220018f7555)

  + ⚙️ Selecione a localidade "Brasil".
      + 🔧![image](https://github.com/user-attachments/assets/b02545f6-5fe8-48e0-859e-0297d9b10f38)
        
  + ⚙️ Selecione a configuração do teclado com base em "Português Brasileiro".
      + 🔧![image](https://github.com/user-attachments/assets/fc710d44-e94d-4c65-8836-fb3293a7f7ff)
         
  + ⚙️ Após o carregamento, essa tela mostrará uma folha na configuração de rede, apenas pressione "Enter" para continuar.
      + 🔧![image](https://github.com/user-attachments/assets/30c48d33-d268-49dc-bcbb-054a294a974d)
         
  + ⚙️ Selecione a opção de "Não configurar a rede agora".
      + 🔧![image](https://github.com/user-attachments/assets/a4530f60-d126-4def-b5c6-de608a580c24)
         
  + ⚙️ Repita o nome da máquina semelhante ao nome inserido anteriormente, seguindo o padrão "cloud-dsm*-ambiente-sistemaoperacional".
      + 🔧![image](https://github.com/user-attachments/assets/87d9efbc-28cd-4743-9b90-da0e685a69f5)

  + ⚙️ Insira o nome do domínio.
      + 🔧![image](https://github.com/user-attachments/assets/4ed3ded8-d7b4-4094-ae05-6b6307ef0325)
           
  + ⚙️ Defina a senha do root de acordo com o padrão pré-estabelecido.
      + 🔧![image](https://github.com/user-attachments/assets/6606acad-db80-4f46-8316-5ea432066381)
         
  + ⚙️ Repita a senha.
      + 🔧![image](https://github.com/user-attachments/assets/86af30fa-f45e-41fa-b2bd-f9807ee6dd58)
   
  + ⚙️ Por fim, insira a senha do "root".
      + 🔧![image](https://github.com/user-attachments/assets/ac190c27-8519-4a3b-b517-5ab37c1fee58)

  + ⚙️ Repita a senha para confirmar.
      + 🔧![image](https://github.com/user-attachments/assets/4285317a-aa4b-418c-a454-bd827007fce0)
   
  + ⚙️ Insira o nome do usuário.
      + 🔧![image](https://github.com/user-attachments/assets/1e4a5707-5b11-4d3f-8208-b26698dead9c)
   
  + ⚙️ Escolha o nome novamente e mantenha o mesmo.
      + 🔧![image](https://github.com/user-attachments/assets/36c63e83-74b8-4644-a547-d3a1f991179c)

  + ⚙️ Insira a senha para do usuário criado.
      + 🔧![image](https://github.com/user-attachments/assets/5b0cd45f-ca72-4639-b278-092fa7f6a70c)
   
  + ⚙️ Para configuração de fuso horário, selecione a opção "São Paulo".
      + 🔧![image](https://github.com/user-attachments/assets/9cfb079a-2c2c-439b-9712-b37717ecd5b0)
   
  + ⚙️ Escolha a opção "Usar o disco inteiro".
      + 🔧![image](https://github.com/user-attachments/assets/6631a3e6-f14e-43dc-ad02-406455fb5210)
           
  + ⚙️ Ainda relacionado a particionamento, selecione a opção disponível conforme a imagem.
      + 🔧![image](https://github.com/user-attachments/assets/c03d5c57-5744-471a-8889-635eb24977fe)
   
  + ⚙️ Selecione a opção para iniciantes.
      + 🔧![image](https://github.com/user-attachments/assets/19f044fc-e12b-4c43-aedf-cd6e6497c797)
   
  + ⚙️ Finalize o processo.
      + 🔧![image](https://github.com/user-attachments/assets/76618924-18b5-4cea-978b-7bfef76f892a)
   
  + ⚙️ Por fim, permita que o processo de formatação do disco inicie.
      + 🔧![image](https://github.com/user-attachments/assets/87462ea8-61a2-4695-a191-bc4f48083ea7)
   
  + ⚙️ Configurar o gerenciador de pacotes.
      + 🔧![image](https://github.com/user-attachments/assets/57688542-e5cc-4017-8d80-827b6d5cc160)
   
  + ⚙️ Definir sobre espelhamento de rede complementar.
      + 🔧![image](https://github.com/user-attachments/assets/cf24eb57-b5da-4ca0-b0ae-903f71a070f4)

  + ⚙️ Configurando popularity-contest.
      + 🔧![image](https://github.com/user-attachments/assets/1f64c506-bbba-4bb4-bf00-529546497296)

  + ⚙️ Neste momento é necessário ter cuidado para selecionar apenas a função "SSH" e "Utilitários de sistema padrão".
      + 🔧![image](https://github.com/user-attachments/assets/02cb96ab-07fe-48d5-9782-5596fa781927)
      > ⚠️ A tela seguinte irá referênciar o GRUB, aceite a instalação e prossiga.

  + ⚙️ Selecione /dev/sda.
      + 🔧![image](https://github.com/user-attachments/assets/7b4f8675-afd7-4cc1-a980-5bb628b1b863)

  + ⚙️ E por fim, você chegou no final da instalação do Debian 12.
      + 🔧![image](https://github.com/user-attachments/assets/c0fd74f7-94ff-4170-8122-37c2a140200d)

  + ⚙️ Por fim, no primeiro contato com o SSH, após inserir o login e a senha, você terá acesso a estela tela.
      + 🔧![image](https://github.com/user-attachments/assets/016f80e5-8864-4185-9df7-3b834afda583)
