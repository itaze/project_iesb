### Projeto de Segurança IESB

Firewall de borda, transparente e tratando blocos de endereçamento baseados no IANA.

Firewall implementado no gateway

### Planejamento

- Objetivo: Implementar firewall que trate o tráfego a nível de protocolo e aplicação. Publicar serviços HTTP e SMTP, com aplicões nginx e postfix respectivamente.

- Justificativa: Uma vez que firewall de pacotes não entrega a segurança necessária, é relevante tratar a nível de aplicação. Onde o comportamento da aplicação baseado em assinaturas, promove filtro mais seguro. Suricata é um IPS/IDS que agrega segurança no ambiente.

- Etapas: Firewall de borda, firewall no gateway, firewall de aplicação.

- Packages: nginx, postfix, pfSense, fail2ban, suricata, iptables.

- Conclusão: Tratamento de firewall com atualizações de regras dinâmicas, regras de boa performance(statless), controles a nível de protocolo de aplicação. Usando pacote de regras do SNORT, publicamos serviços com mais tratamento de segurança.
