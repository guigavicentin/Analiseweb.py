# Analiseweb.py
🔍 AnaliseWeb - Automação de Coleta e Análise de Subdomínios

AnaliseWeb é uma ferramenta de automação para análise inicial de subdomínios, verificação de serviços web e mapeamento de portas abertas. Ideal para pentesters e pesquisadores de segurança que querem ganhar tempo na fase de reconhecimento!

🚀 Como funciona?

1️⃣ Coleta subdomínios usando ShodanX, Subcat e Amass.

2️⃣ Verifica quais domínios respondem e obtém detalhes com Httpx.

3️⃣ Separa os IPs e realiza um Nmap -p- para encontrar portas abertas.

4️⃣ Opcionalmente, executa um Nmap -sV para identificar versões dos serviços.

📌 Requisitos

Python 3

Ferramentas: shodanx, subcat, amass, httpx, nmap

Permissões adequadas para execução dos comandos

🎯 Como usar
python3 analiseweb.py  

Digite o domínio alvo e acompanhe a mágica acontecer! 🔥

📷 Preview

⚠️ Aviso

⚠️ Uso apenas para fins educacionais e testes de segurança autorizados! O uso indevido pode gerar problemas legais.


💡 Sugestões e melhorias são sempre bem-vindas! Abra uma issue ou faça um PR. 🚀
