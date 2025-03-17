
<img align="right" src="https://github.com/user-attachments/assets/1c105e80-a49b-4670-b643-9fdbdbca4465" width="200"> 
</br></br></br>

# Descomplicando o Istio  ⛵

### Sobre a organização das pastas 
O respositório está divido em pastas com base no que foi aprendido. Os arquivos não estão 100% organizados, durante todo o curso foram feitas implementações com foco em aprender sobre os recursos, por conta disso, não houve enfáse na organização do código. Ao percorrer as pastas serão encontrados comentários. As pastas presentes nesse repositório:  
- 📁 day01and02
- 📁 day-03
- 📁 day-04
- 📁 kind


> [!NOTE]
> Para usar o kubernetes na minha máquina pessoal usei o Kubernetes in Docker - **Kind**. Desse modo consegui usar o Kubernetes e o Istio.
> Saiba mais na [Documentação](https://kind.sigs.k8s.io/).
</br>

### 🔑 Conceitos chaves: 
> [!IMPORTANT]
> Compreessão e intendimento amplo sobre os states e sua importância no terraform para manter um ambiente estável e mutável quando existir a necessidade, sem tranformar o ambiente em uma bola de neve 🌨️. Controle sobre o terraform workflow 🌊.
> Conhecimento sobre os principais comandos desde a execução até a movimentação feita por trás dos panos pelo próprio terraform 🚧.
</br>

## 📜  Resumo de alguns aprendizados obtidos durarante a realização das aulas:
- Funcionamento de cada tipo de bloco de código dentro do terraform e sua função: variables, data block, local variables, etc.
- Como utilizar múltiplos providers em um mesmo ambiente terraform.
- Gerar chaves SSH junto com o terraform TLS Provider.
- Debugar o terraform, como ativar essa opção e desativa-lá.
- State Locking - controle sobre as execuções de alterações e atualizações no terraform state, ou seja, enquanto um usuário estiver executando qualquer ação o outro será barrado até o termino da execução atual. Isso evita problemas no controle do terraform state. 
- Gerar revisar e aplicar um deploy usando o comando - terraform plan 
- Terraform cloud, como usar de formar correta e gerenciar equipes.
- Uso do terraform Graph para gerar um fluxograma/digrama do código terraform.
- Resource Life Cycle - um controle mais cirúrgico sobre o processo de criação e exclusão de um recurso, podendo assim determinar de que forma as ações serão executadas.
- O uso de Secrets junto com o Vault.  
<br>

> [!NOTE]
> ### Todos esses recursos foram explorados durante o curso:
> Variables · Local variables · Data Block · Configuration Block · Module Block · OutputBlock ·  Providers ·  TLS Provider ·  Provisioners · Taints · Replace ·  Workspaces · Debugging · Modules · Module Source · Inputs · Terraform Workflow · terraform init · terraform plan · terraform destroy · State locking · Default Backend · Backend Authentication · Backeend Storage · Remote State · Secrets · Vault · Life Cycle · etc.

</br>

> O certificado de conclusão do curso está no Linkedin.
> </br>
> <a href="https://www.linkedin.com/in/-ribeiro/details/certifications/" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
