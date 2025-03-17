
<img align="right" src="https://github.com/user-attachments/assets/1c105e80-a49b-4670-b643-9fdbdbca4465" width="200"> 
</br></br></br></br>

# Descomplicando o Istio  ⛵

### Sobre a organização das pastas 
O respositório está divido em pastas com base no que foi aprendido em cada dia. Durante o processo de aprendizado foram feitas modificações no configuração default que vem do Istio. Segue uma orientação sobre a organização do repositório:  
- 📁 day01and02
- 📁 day-03
- 📁 day-04
- 📁 kind - Dentro desta pasta existe um manifesto em yaml para a criação de um cluster usando o Kind. 


> [!NOTE]
> Para usar o kubernetes na minha máquina pessoal usei o Kubernetes in Docker - **Kind**. Desse modo consegui usar o Kubernetes e o Istio.
> Saiba mais na [Documentação](https://kind.sigs.k8s.io/).
> Também deixo aqui o link para a [documentação](https://istio.io/latest/docs/setup/getting-started/#download) do Istio.
</br>

### 🔑 Conceitos chaves: 
> [!IMPORTANT]
> O Istio não resolve problemas relacionados há performance, ou seja, se sua aplicação/cluster está bixado de nada adianta tentar resolver somente com o Istio. Ela atua na layer 7, também ajuda a termos um controle maior da nossa aplicação, além, de uma camada a mais de segurança, pois, podemos usar o MTLS - Mutual Transport Layer Security de diferentes maneiras dentro da nossa aplicação. p
</br>

## 📜  Resumo de alguns aprendizados obtidos durarante a realização das aulas:
- Sidecar - Atua do lado da aplicação efetuando controle de trafego, balanciamento, e muito mais tudo isso de acordo com as configurações que definimos. 
- Controle do tráfego usando policys, criando assim regras de egress (tráfego de saída) e ingress (tráfego de entrada).
- Mutual Transport Layer Security (MTLS) que pode ser aplicado de diferentes formas.
- Canary - Balancear a carga da aplicação de acordo com a necessidade, com base em um percentual, exemplo de um caso de uso: saiu um versão nova de um componente, nós podemos testar a funcionabilidade dele sem aplicarmos isso para todos os usuários, apenas para uma pequena parte deles com doses homeopaticas e validando a aceitação dele assim como seus possíveis bugs. Esse é um exemplo, mas, é possível usarmos esse recurso para diversas outras demandas.
- Integração de coletores de métricas - Kiali, Grafana, Prometheus, dentre outros meios de coletar e visualizar métricas da aplicação de forma objetiva e simples. 
<br>

> [!NOTE]
> ### Todos esses recursos foram explorados durante o curso:
> Variables · Local variables · Data Block · Configuration Block · Module Block · OutputBlock ·  Providers ·  TLS Provider ·  Provisioners · Taints · Replace ·  Workspaces · Debugging · Modules · Module Source · Inputs · Terraform Workflow · terraform init · terraform plan · terraform destroy · State locking · Default Backend · Backend Authentication · Backeend Storage · Remote State · Secrets · Vault · Life Cycle · etc.

</br>

> O certificado de conclusão do curso está no Linkedin.
> </br>
> <a href="https://www.linkedin.com/in/-ribeiro/details/certifications/" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
