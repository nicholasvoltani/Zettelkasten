---
Date: 2023-03-01
tags:
  - transient
  - hacking
---
up:: 

> "**Se nada coletaste, nada analisarás**"

# Varredura ICMP: *pinging*
- https://hunter.io: permite verificar se emails são válidos
- `fping`: permite *pingar* IPs em **ranges de portas**
- `(Go) assetfinder`: usa vários locais para identificar subdomínios (até mesmo Wayback Machine, etc!)
- `(Go) httprobe`: identifica **sites ativos** (http/https)
	- Note que **pode ter casos com erro 404**: retornar `404 - Not Found` é **diferente** de o site não existir! (Em particular em **portas diferentes**!)

# Port Scanning
> Cada *port* possui algum **software** rodando: SSH, MySQL, FTP, servidor Web, etc
- `nmap`

# Scanners
- **Extensão Browser**: `Wappalyzer`: Permite enxergar plugins/serviços/sistema operacional em um IP/Port
- `nessus`
- `nmap --script vuln <IP>`
- `dirb`: encontra subdiretórios
- `wpscan`: scanning para WordPress



---
### Referências
- Curso **Técnicas de Invasão** (Bruno Fraga)
- FRAGA, Bruno (& VANGLLER, Thompson). **Técnicas de Invasão: aprenda as técnicas usadas por hackers em invasões reais**. São Paulo: Labrador, 2019.
	- Capítulo 5: "Analisar"
	- Capítulo 6: "Análise de Vulnerabilidades"