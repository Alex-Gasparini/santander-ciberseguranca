# santander-ciberseguranca

Para o desafio final, foram utilizadas as seguintes ferramentas:
 
  # Oracle VirtualBox:
    * Criação de duas máquinas virtuais para o ambiente virtual(Kali e Meta)

    Kali Linux surgiu em 2013 como o sucessor do BackTrack Linux, uma distribuição focada em testes de penetração e segurança cibernética. Desenvolvido pela Offensive Security, o Kali é baseado no Debian e oferece uma vasta coleção de ferramentas especializadas, mantendo-se atualizado para o cenário da segurança digital. 
    Origem: A história do Kali Linux começou com o desenvolvimento de sistemas operacionais para testes de segurança, como o Whoppix e o WHAX{/nav}}, que foram combinados para formar o BackTrack.
    Backtrack{/nav>>: Lançado em 2006, o BackTrack ganhou popularidade por sua gama de ferramentas de segurança, tornando-se um padrão de mercado.
    Lançamento do Kali Linux: Em 2013, a Offensive Security lançou o Kali Linux como uma evolução do BackTrack, trazendo melhorias, um processo de desenvolvimento simplificado e uma base no Debian.
    Propósito: O sistema foi projetado para profissionais e entusiastas de segurança da informação, testes de penetração e análise forense.
    Desenvolvimento: Desde o lançamento, o Kali Linux é um projeto de código aberto que prospera com contribuições da comunidade e atualizações constantes. Ele continua a evoluir, com mudanças como a adoção do Xfce como interface padrão e do Zsh como shell padrão em versões mais recentes. 

    O Metasploitable 2 é uma máquina virtual (VM) intencionalmente vulnerável que serve como um ambiente seguro para treinamento em segurança cibernética e testes de penetração. Não possui uma "história" narrativa complexa, mas sim um propósito funcional e um contexto de desenvolvimento: 
    Origem e Propósito: Foi desenvolvido pela comunidade de segurança e é mantido pela Rapid7, a empresa por trás do Metasploit Framework. O objetivo principal é fornecer um "saco de pancadas" legal e seguro para       que profissionais e estudantes possam praticar o uso de ferramentas de segurança, como o Metasploit, sem causar danos a sistemas reais ou redes de produção.
    Lançamento: O Metasploitable 2 foi anunciado e lançado publicamente em junho de 2012.
    Base Técnica: A VM é uma distribuição Linux Ubuntu com várias falhas de segurança e serviços de rede desatualizados e vulneráveis ativamente configurados. Diferentemente de outras VMs vulneráveis que focam em       falhas de aplicações específicas, o Metasploitable 2 concentra-se em vulnerabilidades de sistema operacional e serviços de rede. 
    Em resumo, a história do Metasploitable 2 é a história de uma ferramenta educacional que preencheu uma lacuna na formação prática de cibersegurança, permitindo que as pessoas aprendessem a explorar          vulnerabilidades em um ambiente controlado.
  Em resumo a criação das máquinas são bem intuitivas, gerando poucos problemas, a unica parte que de fato gerou algum foi na montagem da imagem dos sistemas, que devem ser acrescentadas através de "Midia"/ incluindo o caminho do download. 
  
  # Nmap:
    * O Nmap foi lançado pela primeira vez em setembro de 1997, como um artigo na Phrack Magazine com o código-fonte incluído, e foi desenvolvido por Gordon "Fyodor" Lyon. Desde então, evoluiu significativamente através de contribuições da comunidade de segurança de computadores, incluindo o desenvolvimento de recursos como a detecção de sistema operacional, detecção de serviço, o Nmap Scripting Engine (NSE) e o suporte a novos protocolos como IPv6. 
  O Nmap foi utilizado para localizar as portas com vulnerabilidade do IP vitima, ex de codigo utilizado (nmap -sV -p 21,22,80,445 seguido do Ip da vitima. Mostrando quais estavam no status OPEN, ou seja, que oferecem um caminho aberto a vitima.
  # Medusa:
    * Para produzir ataques e assim descobrir dados sensiveis da máquina vitima, utilizando métodos para descobrir senhas de acesso, ataque de força bruta, sprayng etc.
    
