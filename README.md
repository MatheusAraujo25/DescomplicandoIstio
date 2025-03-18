
<img align="right" src="https://github.com/user-attachments/assets/1c105e80-a49b-4670-b643-9fdbdbca4465" width="200"> 
</br></br></br></br>

# Descomplicando o Istio  ⛵

### Sobre a organização das pastas 
O respositório está divido em pastas com base no que foi aprendido em cada dia. Durante o processo de aprendizado foram feitas modificações na configuração default que vem do Istio - Bookinfo Application. Segue uma orientação sobre a organização do repositório:  
- 📁 day01and02
- 📁 day-03
- 📁 day-04
- 📁 kind - Aqui dentro existe um manifesto em yaml para a criação de um cluster usando o Kind. 


> [!NOTE]
> Para usar o Kubernetes na minha máquina pessoal usei o Kubernetes in Docker - famoso **Kind**. Desse modo consegui usar o Kubernetes e o Istio.
> Saiba mais na [Documentação](https://kind.sigs.k8s.io/).
> Também deixo aqui o link para a [documentação](https://istio.io/latest/docs/setup/getting-started/#download) do Istio.
</br>

### 🔑 Conceitos chaves: 
> [!IMPORTANT]
> O Istio não resolve problemas relacionados há performance, ou seja, se sua aplicação/cluster está bixado de nada adianta tentar resolver com o Istio. Ele atua na layer 7, também ajuda a termos um controle maior da nossa aplicação, além, de camadas a mais de segurança, tudo isso sem modificarmos o nosso cluster Kubernetes, só mexendo nas configurações do Istio. Para usarmos ele é recomendado que à aplicação esteja consolidada é bem estruturada para que possamos usufrui de todos os benefícios da melhor forma. 
</br>

## 📜  Resumo de alguns aprendizados obtidos durarante a realização das aulas:
- Como funciona o sidecar - Atua do lado da aplicação, ou seja, ele pode ser usado para efetuar o controle de trafego, balanciamento de carga, e muito mais tudo isso de acordo com as configurações que definimos. 
- Controle do tráfego usando policys, criando assim regras de egress (tráfego de saída) e ingress (tráfego de entrada).
- Mutual Transport Layer Security (MTLS) que pode ser aplicado de diferentes formas, por padrão ele é utilizado no sidecars e workloads.
- Canary - Balanciador de cargar com base em pesos, exemplo de um caso de uso: saiu um versão nova de um componente, podemos testar ele sem aplicarmos isso para todos os usuários, apenas para uma pequena parcela deles em doses homeopaticas, deste modo, conseguimos ter uma maior controle sobre esse componente e a sua aceitação assim como seus possíveis bugs. Esse é um dos exemplo, mas, é possível usarmos esse recurso para diversas outras demandas.
- Integração de coletores de métricas - Kiali, Grafana, Prometheus, dentre outros meios de coletar e visualizar métricas da aplicação de forma objetiva e simples que vem junto a ele.
- Conseguimos testar o delay suportado pela nossa aplicação, ou seja, o tempo máximo de espera na entrega de um conteúdo antes que a aplicação retorne um erro e quebre - Fault Injection.
- Uso do helm junto com o Istio.   
<br>

> [!NOTE]
> ### Todos esses recursos foram explorados durante o curso:
>  MTLS ·Destination Rules · Policys · Workloads · Kiali · Grafana · Prometheus · Fault Injection · Traffic Shifting · TCP Traffic Shifting · Ingres · Bookinfo Application ·······

</br>

> O certificado de conclusão do curso está no Linkedin.
> </br>
> <a href="https://www.linkedin.com/in/-ribeiro/details/certifications/" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
