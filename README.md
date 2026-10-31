<h1 align="center">Servidor Caseiro de Baixo Custo</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Hardware-Caseiro-informational" alt="Hardware caseiro" />
  <img src="https://img.shields.io/badge/Placa--m%C3%A3e-IPMH81G1-blue" alt="Placa-mãe IPMH81G1" />
  <img src="https://img.shields.io/badge/CPU-Intel%20i5--4570-0071C5?logo=intel&logoColor=white" alt="Intel Core i5-4570" />
  <img src="https://img.shields.io/badge/SO-Xubuntu-E95420?logo=ubuntu&logoColor=white" alt="Xubuntu" />
  <img src="https://img.shields.io/badge/Containers-Docker-2496ED?logo=docker&logoColor=white" alt="Docker" />
</p>

## Visão geral

Documentação de um servidor doméstico montado com componentes reaproveitados e de baixo custo. O servidor centraliza:

- backup de arquivos;
- sincronização de saves de jogos;
- downloads via torrent;
- automação residencial;
- execução de containers Docker.

O equipamento usa **dual boot** em dois discos separados: uma distribuição Linux para os serviços e um sistema voltado para jogos.

**Orçamento inicial:** R$ 634,72.

---

## Galeria

<p align="center">
  <picture>
    <source srcset="img/img1.avif" type="image/avif" />
    <source srcset="img/img1.webp" type="image/webp" />
    <img src="img/img1.jpg" width="200" alt="Placa-mãe IPMH81G1 sobre saco antiestático" loading="lazy" />
  </picture>
  <picture>
    <source srcset="img/img2.avif" type="image/avif" />
    <source srcset="img/img2.webp" type="image/webp" />
    <img src="img/img2.jpg" width="200" alt="Montagem com parafusadeira e fonte de alimentação" loading="lazy" />
  </picture>
  <picture>
    <source srcset="img/img3.avif" type="image/avif" />
    <source srcset="img/img3.webp" type="image/webp" />
    <img src="img/img3.jpg" width="200" alt="Gabinete aberto com a placa-mãe instalada" loading="lazy" />
  </picture>
  <picture>
    <source srcset="img/img4.avif" type="image/avif" />
    <source srcset="img/img4.webp" type="image/webp" />
    <img src="img/img4.jpg" width="200" alt="Bancada de montagem" loading="lazy" />
  </picture>
</p>

---

## Custos

<table width="100%">
  <thead>
    <tr><th align="left" width="60%">Peça</th><th align="left" width="20%">Valor</th><th align="left" width="20%">Origem</th></tr>
  </thead>
  <tbody>
    <tr><td>Gabinete Gamer Microcraft III (CG-03RC)</td><td>R$ 255,72</td><td>OLX/MG</td></tr>
    <tr><td>Kit placa-mãe, processador i5-4570, 16 GB DDR3 e fonte 500 W</td><td>R$ 379,00</td><td>OLX/DF</td></tr>
    <tr><td>Placa Wi-Fi 6 e Bluetooth 5.2</td><td>R$ 124,33</td><td>OLX/DF</td></tr>
  </tbody>
</table>

**Subtotal das peças listadas:** R$ 759,05

---

## Hardware

### Configuração atual

<table width="100%">
  <thead>
    <tr><th align="left" width="30%">Componente</th><th align="left" width="70%">Especificação</th></tr>
  </thead>
  <tbody>
    <tr><td>Processador</td><td>Intel Core i5-4570, 4 núcleos, 4 threads, 3,2 GHz (turbo até 3,6 GHz)</td></tr>
    <tr><td>Memória RAM</td><td>16 GB DDR3 1600 MHz</td></tr>
    <tr><td>Armazenamento</td><td>1x SSD de 1 TB (um para o Xubuntu, outro para o Batocera)</td></tr>
    <tr><td>Placa de vídeo</td><td>Intel HD Graphics 4600 (integrada)</td></tr>
    <tr><td>Fonte de alimentação</td><td>500 W reais</td></tr>
    <tr><td>Gabinete</td><td>Micro-ATX com ventilação frontal e traseira</td></tr>
  </tbody>
</table>

### Placa-mãe IPMH81G1

<table width="100%">
  <thead>
    <tr><th align="left" width="30%">Componente</th><th align="left" width="70%">Especificação</th></tr>
  </thead>
  <tbody>
    <tr><td>Socket</td><td>LGA 1150 (Intel Core 4ª geração, Xeon E3 v3)</td></tr>
    <tr><td>Chipset</td><td>Intel H81 Express</td></tr>
    <tr><td>Fator de forma</td><td>Micro-ATX</td></tr>
    <tr><td>Memória</td><td>2x DDR3 DIMM, até 16 GB, 1333/1600 MHz</td></tr>
    <tr><td>Vídeo onboard</td><td>Intel HD Graphics (HDMI e VGA)</td></tr>
    <tr><td>Áudio onboard</td><td>Realtek ALC662, 3 conexões (Line Out, Line In, Mic)</td></tr>
    <tr><td>Rede onboard</td><td>Realtek RTL8111, Gigabit Ethernet</td></tr>
    <tr><td>Portas SATA</td><td>2x SATA 3.0 + 2x SATA 2.0</td></tr>
    <tr><td>USB traseiro</td><td>2x USB 3.0 + 4x USB 2.0</td></tr>
    <tr><td>Expansão</td><td>1x PCIe x16, 2x PCIe x1</td></tr>
    <tr><td>Saídas de vídeo</td><td>1x HDMI + 1x VGA</td></tr>
    <tr><td>PS/2</td><td>1x teclado + 1x mouse</td></tr>
    <tr><td>Painel frontal</td><td>2x USB 2.0, áudio, power/reset</td></tr>
    <tr><td>M.2 NVMe</td><td>Não possui (somente com adaptador PCIe)</td></tr>
    <tr><td>USB-C</td><td>Não possui (somente com adaptador PCIe)</td></tr>
    <tr><td>BIOS</td><td>AMI</td></tr>
    <tr><td>Alimentação</td><td>24 pinos ATX + 4 pinos CPU</td></tr>
  </tbody>
</table>

---

## Sistemas operacionais (dual boot)

<table width="100%">
  <thead>
    <tr><th align="left" width="30%">Sistema</th><th align="left" width="70%">Função</th></tr>
  </thead>
  <tbody>
    <tr><td>Xubuntu</td><td>Sistema principal. Executa os serviços em Docker.</td></tr>
    <tr><td>Batocera</td><td>Distribuição Linux para emulação de jogos antigos.</td></tr>
    <tr><td>Bazzite ou HoloISO</td><td>Sistemas baseados em SteamOS para jogos modernos via Steam (a escolher).</td></tr>
  </tbody>
</table>

---

## Funcionalidades e serviços

<table width="100%">
  <thead>
    <tr><th align="left" width="30%">Funcionalidade</th><th align="left" width="70%">Descrição</th></tr>
  </thead>
  <tbody>
    <tr><td>Servidor de arquivos</td><td>Backup centralizado.</td></tr>
    <tr><td>Sincronização de saves</td><td>Saves de jogos sincronizados via Syncthing.</td></tr>
    <tr><td>Downloads</td><td>Torrents e arquivos.</td></tr>
    <tr><td>Casa inteligente</td><td>Dispositivos da rede Tuya e controladores ESP32.</td></tr>
    <tr><td>Automações</td><td>Fluxos locais via n8n e Evolution API.</td></tr>
  </tbody>
</table>

### Containers Docker

<table width="100%">
  <thead>
    <tr><th align="left" width="30%">Serviço</th><th align="left" width="70%">Função</th></tr>
  </thead>
  <tbody>
    <tr><td><a href="https://n8n.io/"><img src="https://img.shields.io/badge/n8n-Workflow%20Automation-EA4B71?logo=n8n&logoColor=white" alt="n8n" /></a></td><td>Automação de fluxos de trabalho com interface visual.</td></tr>
    <tr><td><img src="https://img.shields.io/badge/Evolution%20API-Integra%C3%A7%C3%A3o-25D366?logo=whatsapp&logoColor=white" alt="Evolution API" /></td><td>Integração de serviços e aplicativos.</td></tr>
    <tr><td><a href="https://casaos.io/"><img src="https://img.shields.io/badge/CasaOS-Gerenciamento%20Dom%C3%A9stico-1DB954" alt="CasaOS" /></a></td><td>Gerenciamento de dispositivos domésticos.</td></tr>
    <tr><td><a href="https://www.netdata.cloud/"><img src="https://img.shields.io/badge/Netdata-Monitoramento-00AB44?logo=netdata&logoColor=white" alt="Netdata" /></a></td><td>Monitoramento de recursos do sistema em tempo real.</td></tr>
    <tr><td><a href="https://easypanel.io/"><img src="https://img.shields.io/badge/Easypanel-Aplica%C3%A7%C3%B5es-000000" alt="Easypanel" /></a></td><td>Painel de gerenciamento de aplicações e serviços.</td></tr>
    <tr><td><a href="https://www.home-assistant.io/"><img src="https://img.shields.io/badge/Home%20Assistant-Automa%C3%A7%C3%A3o-18BCF2?logo=homeassistant&logoColor=white" alt="Home Assistant" /></a></td><td>Automação residencial.</td></tr>
    <tr><td><a href="https://www.portainer.io/"><img src="https://img.shields.io/badge/Portainer-Containers-13BEF9?logo=portainer&logoColor=white" alt="Portainer" /></a></td><td>Gerenciamento de containers Docker.</td></tr>
    <tr><td><a href="https://syncthing.net/"><img src="https://img.shields.io/badge/Syncthing-Sync%20Files-0891D1?logo=syncthing&logoColor=white" alt="Syncthing" /></a></td><td>Sincronização de arquivos P2P.</td></tr>
    <tr><td><img src="https://img.shields.io/badge/MySpeed-Teste%20de%20velocidade-blue" alt="MySpeed" /></td><td>Teste e monitoramento de velocidade de rede.</td></tr>
    <tr><td><img src="https://img.shields.io/badge/RomM-ROMs%20de%20jogos-purple" alt="RomM" /></td><td>Gerenciamento de ROMs de jogos.</td></tr>
    <tr><td><a href="https://www.zerotier.com/"><img src="https://img.shields.io/badge/ZeroTier-VPN%20e%20Rede-FCC624?logo=zerotier&logoColor=black" alt="ZeroTier" /></a></td><td>Rede virtual privada entre dispositivos.</td></tr>
  </tbody>
</table>

---

## Upgrades previstos

- **Placa-mãe com M.2:** [VEDO Placa-mãe LGA 1150 NGFF M.2](https://www.amazon.com.br/gp/product/B0BVVY1MSC).
- **Processador Intel Core i7-4790** (troca do i5-4570). Fonte: [UserBenchmark](https://cpu.userbenchmark.com/Compare/Intel-Core-i7-4790-vs-Intel-Core-i5-4570/2293vs2770).

<table width="100%">
  <thead>
    <tr><th align="left" width="40%">Especificação</th><th align="left" width="30%">i5-4570 (atual)</th><th align="left" width="30%">i7-4790</th></tr>
  </thead>
  <tbody>
    <tr><td>Cores/Threads</td><td>4/4</td><td>4/8</td></tr>
    <tr><td>Frequência base</td><td>3,2 GHz</td><td>3,6 GHz</td></tr>
    <tr><td>Frequência turbo</td><td>3,6 GHz</td><td>4,0 GHz</td></tr>
    <tr><td>Cache L3</td><td>6 MB</td><td>8 MB</td></tr>
    <tr><td>TDP</td><td>84 W</td><td>84 W</td></tr>
    <tr><td>Benchmark (UserBenchmark)</td><td>3,27</td><td>4,53</td></tr>
    <tr><td>Desempenho geral</td><td>Referência</td><td>+38,5%</td></tr>
  </tbody>
</table>
