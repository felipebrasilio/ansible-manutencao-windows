🚀 Automatizando a Manutenção de Servidores Windows com Ansible

Manter servidores Windows performáticos e livres de problemas exige uma rotina eficiente de manutenção. 
Para facilitar esse processo, desenvolvi um playbook Ansible que automatiza tarefas essenciais de limpeza, otimização e verificação do sistema.
Com essa automação, seus servidores estarão sempre otimizados, seguros e funcionando sem interrupções!

O que essa automação faz?
✅ Limpa arquivos temporários e cache do sistema (Temp, Prefetch, %TEMP%)

✅ Otimiza o Windows Update (remove arquivos corrompidos do SoftwareDistribution)

✅ Remove logs antigos e logs de eventos do Windows

✅ Verifica e repara o disco (chkdsk)

✅ Verifica e corrige arquivos do sistema (sfc e DISM)

✅ Otimiza e desfragmenta o disco (Optimize-Volume)

✅ Libera memória RAM (limpeza de cache do sistema)

✅ Limpa cache DNS para resolver problemas de rede

✅ Remove pacotes obsoletos do Windows Update

✅ Reinicia automaticamente o servidor, se necessário (opcional)
