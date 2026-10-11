# Scheduling System — Front-end

Painel web para cadastro e gerenciamento de agendamentos, integrado a uma API REST em Java.

**Tecnologias:** HTML · CSS · JavaScript  
**Status:** Projeto demonstrativo de integração front-end / back-end.

## Funcionalidades da interface
- Cadastro de agendamentos com cliente, serviço, data, hora e observações.
- Visão geral por status: pendente, confirmado, cancelado e concluído.
- Listagem e filtros por status.
- Ações de atualização de situação e exclusão.

## Como executar
1. Execute o back-end do [scheduling-api](https://github.com/fgscarvalho37-a11y/scheduling-api).
2. Confira a constante `API` em `index.html`. O endereço atual é `http://localhost:8083/api/appointments`.
3. Sirva os arquivos em um servidor HTTP local:

```bash
git clone https://github.com/fgscarvalho37-a11y/scheduling-front.git
cd scheduling-front
python -m http.server 5500
```

Acesse `http://localhost:5500`. Ajuste a configuração da API/CORS caso use outra porta ou domínio.

## Back-end
[Ver repositório scheduling-api](https://github.com/fgscarvalho37-a11y/scheduling-api).

Desenvolvido por [Felipe Gomes](https://github.com/fgscarvalho37-a11y).