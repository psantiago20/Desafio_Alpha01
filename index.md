# Resumo do Curso — Hard & Soft Skills
![Progresso](https://img.shields.io/badge/Progresso-3%20Módulos-blue)
![Markdown](https://img.shields.io/badge/Markdown-Avançado-green)
![Trilhas](https://img.shields.io/badge/Trilhas-Hard%20%2F%20Soft-orange)

---

# Professores

| ![Kenji](kenji.jpeg) | ![Prof2](URL_FOTO_PROF2) | ![Prof3](URL_FOTO_PROF3) |
|---|---|---|
| **Kenji Taniguchi**  <br> [LinkedIn](https://www.linkedin.com/in/kenjitaniguchi/) · [GitHub](https://github.com/) | **Professor 2** <br> [LinkedIn](https://linkedin.com) · [Instagram](https://instagram.com) | **Professor 3** <br> [LinkedIn](https://linkedin.com) · [Instagram](https://instagram.com) |

---

# Navegação
- [Hard Skills](#hard-skills)
- [Soft Skills](#soft-skills)
- [Estatísticas](#estatísticas-gerais)

---

# Hard Skills

## 1) Redes de Computadores
<details>
<summary><strong>➤ Clique para abrir</strong></summary>

### Tipos de Redes
| Tipo | Alcance | Exemplos |
|------|---------|----------|
| LAN | Local | Casa, empresa |
| WAN | Amplo | Internet |
| MAN | Cidade | Provedores |
| PAN | Pessoal | Bluetooth |

### Topologias
```
        [Switch]
     /     |     \
  PC1    PC2    PC3
```

### HTTP x HTTPS
- **HTTP** → texto puro  
- **HTTPS** → HTTP + TLS  

### Fluxo da Web (Mermaid)
```mermaid
sequenceDiagram
    User->>Browser: Acessa site
    Browser->>DNS: Resolve domínio
    DNS->>Browser: Devolve IP
    Browser->>Servidor: Requisição HTTP/HTTPS
    Servidor->>Browser: Resposta
```

</details>

---

## 2) Protocolos, IP, DNS e Arquitetura
<details>
<summary><strong>➤ Clique para abrir</strong></summary>

### TCP x UDP
| Protocolo | Confiável | Rápido | Uso |
|-----------|-----------|--------|-----|
| TCP | ✔️ | ❌ | Web, email |
| UDP | ❌ | ✔️ | Jogos, VoIP |

### DNS – Registros
- A  
- AAAA  
- CNAME  
- TXT  
- PTR  

### Mapa Mental (Mermaid)
```mermaid
mindmap
  root((Redes))
    Protocolos
      TCP
      UDP
    DNS
      A
      AAAA
      CNAME
    Segurança
      Criptografia
      DDoS
      VPN
```

</details>

---

## 3) Git e Versionamento
<details>
<summary><strong>➤ Clique para abrir</strong></summary>

### Conceitos Básicos
| Conceito | Definição |
|----------|-----------|
| Working Tree | Arquivos reais |
| Index | Staging |
| Commit | Snapshot |
| HEAD | Posição atual |

### Fluxo
```bash
git init
git add .
git commit -m "Inicial"
git branch feature-x
git checkout feature-x
```

### Histórico (Mermaid)
```mermaid
gitGraph
  commit id:"A"
  commit id:"B"
  branch feature
  checkout feature
  commit id:"C"
  checkout main
  merge feature
```

</details>

---

# Soft Skills
<details>
<summary><strong>➤ Clique para abrir</strong></summary>

### Linguagem Corporal
- Postura  
- Olhar  
- Gestos  

### Escuta Ativa
> “Ouvir é biológico. Escutar é intencional.”

Checklist:
- [x] Não interromper  
- [x] Confirmar entendimento  
- [x] Observar sinais  
- [x] Fazer perguntas  

### Feedback
Modelo SCI: **Situação → Comportamento → Impacto**

</details>

---

# Estatísticas Gerais

```mermaid
pie title Domínio Geral
  "Redes" : 33
  "Git" : 33
  "Soft Skills" : 33
```

---

# Fim do Documento
