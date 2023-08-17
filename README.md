<div>
  <h1>Terraform com GitHub Actions: Implementação de VMs na Azure e AWS</h1>
  <h2>Visão Geral</h2>
  <p>Este repositório foca em utilizar as GitHub Actions para automatizar a implantação de máquinas virtuais (VMs) nas
    plataformas Azure e AWS usando o Terraform. Ao integrar as capacidades de "Infraestrutura como Código" (IaC) do
    Terraform com as funcionalidades de integração contínua do GitHub Actions, este projeto visa proporcionar um
    processo de implantação de infraestrutura automatizado e contínuo.</p>
  <h2>Detalhes do Projeto</h2>
  <p>A integração contínua e entrega (CI/CD) são cruciais para otimizar os fluxos de trabalho de desenvolvimento e
    implantação. Nessa combinação, o Terraform desempenha um papel fundamental como ferramenta de "Infraestrutura como
    Código", permitindo a provisionamento, atualização e versionamento da infraestrutura de forma segura e eficiente.
  </p>
  <p>Nesta configuração:</p>
  <ol>
    <li>Um push ou pull request dispara a GitHub Action.</li>
    <li>A ação inicializa o ambiente do Terraform.</li>
    <li>Os planos do Terraform são então aplicados para provisionar:<ul>
        <li>Uma VM na Azure.</li>
        <li>Uma VM na AWS.</li>
      </ul>
    </li>
  </ol>
  <h2>Pré-requisitos</h2>
  <ul>
    <li>Contas ativas na Azure e AWS com as permissões adequadas para criar recursos.</li>
    <li>Terraform configurado e instalado.</li>
  </ul>
  <h2>Utilização</h2>
  <ol>
    <li>Faça fork ou clone deste repositório.</li>
    <li>Configure suas credenciais da Azure e AWS. Por razões de segurança, recomenda-se usar GitHub Secrets para
      gerenciar essas credenciais.</li>
    <li>Modifique os arquivos de configuração do Terraform conforme necessário.</li>
    <li>Faça commit e push das suas alterações.</li>
    <li>A GitHub Action será ativada automaticamente, gerenciando a provisionamento das VMs.</li>
  </ol>
  <h2>Conclusão</h2>
  <p>Este repositório serve como um exemplo ilustrativo de como o Terraform pode ser combinado com as GitHub Actions
    para automatizar o provisionamento de recursos em múltiplas plataformas de nuvem. Feedback e contribuições são muito
    apreciados!</p>
  <p>Para um estudo mais aprofundado e outros projetos, sinta-se à vontade para verificar o meu <a
      href="https://github.com/MessiasOli" target="_new">perfil no GitHub</a>.</p>
</div>