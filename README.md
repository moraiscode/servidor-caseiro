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

**Orçamento informado:** R$ 634,72.

---

## Galeria

<p align="center">
  <picture>
    <source srcset="img1.avif" type="image/avif" />
    <source srcset="img1.webp" type="image/webp" />
    <img src="img1.jpg" width="200" alt="Placa-mãe IPMH81G1 sobre saco antiestático" loading="lazy" />
  </picture>
  <picture>
    <source srcset="img2.avif" type="image/avif" />
    <source srcset="img2.webp" type="image/webp" />
    <img src="img2.jpg" width="200" alt="Montagem com parafusadeira e fonte de alimentação" loading="lazy" />
  </picture>
  <picture>
    <source srcset="img3.avif" type="image/avif" />
    <source srcset="img3.webp" type="image/webp" />
    <img src="img3.jpg" width="200" alt="Gabinete aberto com a placa-mãe instalada" loading="lazy" />
  </picture>
  <picture>
    <source srcset="img4.avif" type="image/avif" />
    <source srcset="img4.webp" type="image/webp" />
    <img src="img4.jpg" width="200" alt="Bancada de montagem" loading="lazy" />
  </picture>
</p>

---

## Custos

| Peça | Valor | Origem |
|------|-------|--------|
| Gabinete Gamer Microcraft III (CG-03RC) | R$ 255,72 | OLX/MG |
| Kit placa-mãe, processador i5-4570, 16 GB DDR3 e fonte 500 W | R$ 379,00 | OLX/DF |
| Placa Wi-Fi 6 e Bluetooth 5.2 | R$ 124,33 | OLX/DF |

**Subtotal das peças listadas:** R$ 759,05

> Observação: o orçamento informado (R$ 634,72) não coincide com o subtotal das peças listadas (R$ 759,05). A diferença ainda não está explicada neste documento.

---

## Hardware

### Configuração atual

| Componente | Especificação |
|------------|---------------|
| Processador | Intel Core i5-4570, 4 núcleos, 4 threads, 3,2 GHz (turbo até 3,6 GHz) |
| Memória RAM | 16 GB DDR3 1600 MHz |
| Armazenamento | 1x SSD de 1 TB (um para o Xubuntu, outro para o Batocera) |
| Placa de vídeo | Intel HD Graphics 4600 (integrada) |
| Fonte de alimentação | 500 W reais |
| Gabinete | Micro-ATX com ventilação frontal e traseira |

### Placa-mãe IPMH81G1

| Componente | Especificação |
|------------|---------------|
| Socket | LGA 1150 (Intel Core 4ª geração, Xeon E3 v3) |
| Chipset | Intel H81 Express |
| Fator de forma | Micro-ATX |
| Memória | 2x DDR3 DIMM, até 16 GB, 1333/1600 MHz |
| Vídeo onboard | Intel HD Graphics (HDMI e VGA) |
| Áudio onboard | Realtek ALC662, 3 conexões (Line Out, Line In, Mic) |
| Rede onboard | Realtek RTL8111, Gigabit Ethernet |
| Portas SATA | 2x SATA 3.0 + 2x SATA 2.0 |
| USB traseiro | 2x USB 3.0 + 4x USB 2.0 |
| Expansão | 1x PCIe x16, 2x PCIe x1 |
| Saídas de vídeo | 1x HDMI + 1x VGA |
| PS/2 | 1x teclado + 1x mouse |
| Painel frontal | 2x USB 2.0, áudio, power/reset |
| M.2 NVMe | Não possui (somente com adaptador PCIe) |
| USB-C | Não possui (somente com adaptador PCIe) |
| BIOS | AMI |
| Alimentação | 24 pinos ATX + 4 pinos CPU |

---

## Sistemas operacionais (dual boot)

| Sistema | Função |
|---------|--------|
| Xubuntu | Sistema principal. Executa os serviços em Docker. |
| Batocera | Distribuição Linux para emulação de jogos antigos. |
| Bazzite ou HoloISO | Sistemas baseados em SteamOS para jogos modernos via Steam (a escolher). |

---

## Funcionalidades e serviços

| Funcionalidade | Descrição |
|----------------|-----------|
| Servidor de arquivos | Backup centralizado. |
| Sincronização de saves | Saves de jogos sincronizados via Syncthing. |
| Downloads | Torrents e arquivos. |
| Casa inteligente | Dispositivos da rede Tuya e controladores ESP32. |
| Automações | Fluxos locais via n8n e Evolution API. |

### Containers Docker

| Serviço | Função |
|---------|--------|
| [![n8n](https://img.shields.io/badge/n8n-Workflow%20Automation-EA4B71?logo=n8n&logoColor=white)](https://n8n.io/) | Automação de fluxos de trabalho com interface visual. |
| ![Evolution API](https://img.shields.io/badge/Evolution%20API-Integra%C3%A7%C3%A3o-25D366?logo=whatsapp&logoColor=white) | Integração de serviços e aplicativos. |
| [![CasaOS](https://img.shields.io/badge/CasaOS-Gerenciamento%20Dom%C3%A9stico-1DB954)](https://casaos.io/) | Gerenciamento de dispositivos domésticos. |
| [![Netdata](https://img.shields.io/badge/Netdata-Monitoramento-00AB44?logo=netdata&logoColor=white)](https://www.netdata.cloud/) | Monitoramento de recursos do sistema em tempo real. |
| [![Easypanel](https://img.shields.io/badge/Easypanel-Aplica%C3%A7%C3%B5es-000000)](https://easypanel.io/) | Painel de gerenciamento de aplicações e serviços. |
| [![Home Assistant](https://img.shields.io/badge/Home%20Assistant-Automa%C3%A7%C3%A3o-18BCF2?logo=homeassistant&logoColor=white)](https://www.home-assistant.io/) | Automação residencial. |
| [![Portainer](https://img.shields.io/badge/Portainer-Containers-13BEF9?logo=portainer&logoColor=white)](https://www.portainer.io/) | Gerenciamento de containers Docker. |
| [![Syncthing](https://img.shields.io/badge/Syncthing-Sync%20Files-0891D1?logo=syncthing&logoColor=white)](https://syncthing.net/) | Sincronização de arquivos P2P. |
| ![MySpeed](https://img.shields.io/badge/MySpeed-Teste%20de%20velocidade-blue) | Teste e monitoramento de velocidade de rede. |
| ![RomM](https://img.shields.io/badge/RomM-ROMs%20de%20jogos-purple) | Gerenciamento de ROMs de jogos. |
| [![ZeroTier](https://img.shields.io/badge/ZeroTier-VPN%20e%20Rede-FCC624?logo=zerotier&logoColor=black)](https://www.zerotier.com/) | Rede virtual privada entre dispositivos. |

---

## Upgrades previstos

- **Placa-mãe com M.2:** [VEDO Placa-mãe LGA 1150 NGFF M.2](https://www.amazon.com.br/gp/product/B0BVVY1MSC).
- **Processador Intel Core i7-4790** (troca do i5-4570):

  | Especificação | i5-4570 (atual) | i7-4790 |
  |---------------|-----------------|---------|
  | Cores/Threads | 4/4 | 4/8 |
  | Frequência base | 3,2 GHz | 3,6 GHz |
  | Frequência turbo | 3,6 GHz | 4,0 GHz |
  | Cache L3 | 6 MB | 8 MB |
  | TDP | 84 W | 84 W |
  | Benchmark (UserBenchmark) | 3,27 | 4,53 |
  | Desempenho geral | Referência | +38,5% |

  Fonte: [UserBenchmark](https://cpu.userbenchmark.com/Compare/Intel-Core-i7-4790-vs-Intel-Core-i5-4570/2293vs2770)
