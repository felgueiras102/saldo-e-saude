# Saldo & Saúde

Aplicação web e mobile que junta **finanças pessoais** e **saúde/fitness** no mesmo sítio, para perceber como o dinheiro e os hábitos se influenciam.

> 🚧 Projeto em desenvolvimento. Ainda não há nada para correr.

## Objetivos

- Registar despesas e receitas, e definir orçamentos e metas de poupança.
- Registar peso, treinos e refeições.
- Cruzar os dois mundos. Por exemplo: "gastaste 85 € em fast food este mês; se cozinhares em casa, poupas X € e Y kcal".
- Registo rápido na app mobile (menos de 10 segundos) e dashboard com gráficos na web.

## Stack

| Camada | Tecnologia |
|---|---|
| Backend / API | PHP 8 + Symfony, PostgreSQL, Doctrine ORM |
| Web | Twig, JavaScript (Stimulus, Chart.js), CSS |
| Mobile | Flutter (Dart) |
| Infraestrutura | Docker, Docker Compose, GitHub Actions |
| Design | Figma |

## Estrutura do repositório

- `backend/`: API e aplicação web (Symfony)
- `mobile/`: app Flutter
- `design/`: identidade visual e design system
- `docs/`: documentação
- `docker/`: configuração dos contentores
- `.github/`: pipelines e templates

## Como correr

Por escrever. Será preenchido quando o ambiente Docker estiver pronto.

## Estado

Em construção, a seguir um plano por fases.

## Autor

Alexandre Felgueiras ([@felgueiras102](https://github.com/felgueiras102))