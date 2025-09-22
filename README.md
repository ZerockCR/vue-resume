A clean and minimal template for building a resume landing page, powered by **Vue 3** (Composition API) and **B ootstrap 5**.

Key features:
- Uses Vue3 **Composition API**.
- **Six unique section layouts** to showcase your work experience, education, skills, projects, and more.
- Adaptive navigation: **a fixed sidebar** for desktops and **a tabbed layout** for mobile.
- Built-in **multi-language** support.
- Emails with **EmailJS** – no backend needed!
- **Super easy** to customize!

## Getting Started

1. Clone the repo:
```
git clone https://github.com/ryanbalieiro/vue-resume-template
```

2. Go to the project's root folder and use npm to install all required components:
```
npm install
```

3. Launch the project in developer mode:
```
npm run dev
```

4. (Optional) If you'd like to clear all the portfolio data and begin with a blank page with no sections, run the command below:
```
npm run resume:clear
```

5. (Optional) If you want to temporarily deactivate the preload animation during theme adjustments, go to `public/data/settings.json` and set the `preloaderEnabled` flag to false.

## Configuration Tutorial

Watch this step-by-step video tutorial to see exactly how to configure your resume:

| #   | Title                                    | Watch                                                                    |
|-----|------------------------------------------|--------------------------------------------------------------------------|
| 1   | Setting up the project                   | [Watch on YouTube](https://www.youtube.com/watch?v=QvQQK81xljw&t=0m00s)  |
| 2   | Title and colors                         | [Watch on YouTube](https://www.youtube.com/watch?v=QvQQK81xljw&t=1m31s)  |
| 3   | Settings, strings and profile            | [Watch on YouTube](https://www.youtube.com/watch?v=QvQQK81xljw&t=4m20s)  |
| 4   | Categories and sections                  | [Watch on YouTube](https://www.youtube.com/watch?v=QvQQK81xljw&t=7m37s)  |
| 5   | ArticleProfile                           | [Watch on YouTube](https://www.youtube.com/watch?v=QvQQK81xljw&t=10m33s) |
| 6   | ArticleTimeline                          | [Watch on YouTube](https://www.youtube.com/watch?v=QvQQK81xljw&t=14m12s) |
| 7   | ArticleSkills                            | [Watch on YouTube](https://www.youtube.com/watch?v=QvQQK81xljw&t=18m00s) |
| 8   | ArticlePortfolio                         | [Watch on YouTube](https://www.youtube.com/watch?v=QvQQK81xljw&t=22m38s) |
| 9   | ArticleThreads and ArticleContactOptions | [Watch on YouTube](https://www.youtube.com/watch?v=QvQQK81xljw&t=25m36s) |
| 10  | ArticleContactForm                       | [Watch on YouTube](https://www.youtube.com/watch?v=QvQQK81xljw&t=29m44s) |
| 11  | Deploying on GitHub Pages                | [Watch on YouTube](https://www.youtube.com/watch?v=QvQQK81xljw&t=34m05s) |
| 12  | Extra deployment instructions            | [Watch on YouTube](https://www.youtube.com/watch?v=QvQQK81xljw&t=36m20s) |   

For step-by-step setup and deployment instructions, you can also check out the following docs:
- [CONFIGURATION.md](./docs/CONFIGURATION.md) – learn how to configure and customize the project.
- [DEPLOYMENT.md](./docs/DEPLOYMENT.md) – short guide on deploying the project.

## About
It is based on the [Bootstrap](https://getbootstrap.com/) framework created by Mark Otto and Jacob Thorton; and the [Vue](https://vuejs.org/) framework created by Evan You.

Additional frameworks and plugins used include:
- **Font Awesome**: A library of free vector icons.
- **EmailJS**: A free service that allows you to send emails using JavaScript.
- **PrimeIcons**: Another library of free vector icons.
- **ChartJS**: A free JavaScript library for creating charts and graphs.

---
Comentarios Propios:
Sección Portafolio - sections.json
{
            "id": "portfolio",
            "categoryId": "showcase",
            "jsonPath": "/sections/portfolio.json",
            "faIcon": "fa-solid fa-folder-open",
            "type": "column",
            "locales": {
                "en": {
                    "title": "My *Portfolio*",
                    "title_short": null,
                    "description": "Explore a selection of my recent projects and creative works.",
                    "nav_label": "Portfolio"
                },
                "es": {
                    "title": "*Portafolio* Personal",
                    "title_short": null,
                    "description": "Explora una selección de mis proyectos desarrollados.",
                    "nav_label": "Portafolio"
                }
            }
        },

Sección Aficiones - sections.json
{
            "id": "hobbies",
            "categoryId": "more",
            "jsonPath": "/sections/hobbies.json",
            "faIcon": "fa-solid fa-heart",
            "type": "column",
            "locales": {
                "en": {
                    "title": "*Hobbies* & Interests",
                    "title_short": null,
                    "description": "This is pretty much how I spend my free time:",
                    "nav_label": "Hobbies"
                },
                "es": {
                    "title": "*Pasatiempos* e Intereses",
                    "title_short": null,
                    "description": "Así es más o menos cómo paso mi tiempo libre:",
                    "nav_label": "Aficiones"
                }
            }
        },

Premios - Achievements
{
            "id": 1,
            "component": "ArticleThread",
            "locales": {
                "en": {"title": "Awards"},
                "es": {"title": "Premios"},
                "fr": {"title": "Prix"},
                "zh": {"title": "奖项"}
            },
            "settings": {
                "order_items_by": "id",
                "order_items_sort": "desc"
            },
            "items": [
                {
                    "id": 1,
                    "dateStart": {"year": 2018, "month": 8},
                    "fallbackFaIcon": "fa-solid fa-university",
                    "fallbackFaIconColor": null,
                    "locales": {
                        "en": {
                            "title": "Best Graduation Project",
                            "description": "Outstanding work on graduation project; recognized for innovation and impact.",
                            "institution": "Harvard University"
                        },

                        "es": {
                            "title": "Mejor Proyecto de Graduación",
                            "description": "Trabajo destacado en proyecto de graduación; reconocido por innovación e impacto.",
                            "institution": "Harvard University"
                        },

                        "fr": {
                            "title": "Meilleur Projet de Fin d'Études",
                            "description": "Travail exceptionnel sur le projet de fin d'études; reconnu pour l'innovation et l'impact.",
                            "institution": "Harvard University"
                        },

                        "zh": {
                            "title": "最佳毕业项目",
                            "description": "在毕业项目上的杰出工作；因创新和影响力受到认可。",
                            "institution": "Harvard University"
                        }
                    },
                    "links": []
                },

                {
                    "id": 2,
                    "dateStart": {"year": 2019, "month": 9},
                    "fallbackFaIcon": "fa-solid fa-university",
                    "fallbackFaIconColor": null,
                    "locales": {
                        "en": {
                            "title": "2nd Place – Alumni UX Hackathon",
                            "description": "Secured 2nd place in Harvard's Alumni UX hackathon; demonstrated creative problem-solving.",
                            "institution": "Harvard University"
                        },

                        "es": {
                            "title": "2do Lugar - Hackathon Alumni de UX",
                            "description": "Obtuvo el 2do lugar en el Hackathon Alumni de UX de Harvard; demostró solución creativa de problemas.",
                            "institution": "Universidad de Harvard"
                        },

                        "fr": {
                            "title": "2e Place - Hackathon UX des Anciens",
                            "description": "Obtenu la 2e place au hackathon UX des anciens de Harvard; démontré la résolution créative de problèmes.",
                            "institution": "Université Harvard"
                        },

                        "zh": {
                            "title": "第二名 - 校友UX黑客马拉松",
                            "description": "在哈佛校友UX黑客马拉松中获得第二名；展示了创造性问题解决能力。",
                            "institution": "哈佛大学"
                        }
                    },
                    "links": [
                        {"href": "https://harvard.com", "stringKey": "view_more_info"}
                    ]
                },

                {
                    "id": 3,
                    "dateStart": {"year": 2020, "month": 11},
                    "fallbackFaIcon": "fa-solid fa-house-laptop",
                    "fallbackFaIconColor": null,
                    "locales": {
                        "en": {
                            "title": "1st Place – Adobe Creative Jam",
                            "description": "Achieved 1st place in Adobe Creative Jam; showcased design excellence and collaboration.",
                            "institution": "Adobe Inc."
                        },

                        "es": {
                            "title": "1er Lugar - Adobe Creative Jam",
                            "description": "Obtuvo el 1er lugar en Adobe Creative Jam; mostró excelencia en diseño y colaboración.",
                            "institution": "Adobe Inc."
                        },

                        "fr": {
                            "title": "1ère Place - Adobe Creative Jam",
                            "description": "Obtenu la 1ère place à Adobe Creative Jam; mis en avant l'excellence en design et la collaboration.",
                            "institution": "Adobe Inc."
                        },

                        "zh": {
                            "title": "第一名 - Adobe创意盛宴",
                            "description": "在Adobe创意盛宴中获得第一名；展示了卓越的设计和合作。",
                            "institution": "Adobe Inc."
                        }
                    },
                    "links": []
                },

                {
                    "id": 4,
                    "dateStart": {"year": 2023, "month": 3},
                    "fallbackFaIcon": "fa-solid fa-newspaper",
                    "fallbackFaIconColor": null,
                    "locales": {
                        "en": {
                            "title": "Article Mention – UX Contribution",
                            "description": "Featured in Forbes for outstanding UX contributions; impactful designs and insights.",
                            "institution": "Forbes"
                        },

                        "es": {
                            "title": "Mención en Artículo - Contribución a UX",
                            "description": "Destacado en Forbes por sobresalientes contribuciones a UX; diseños e ideas impactantes.",
                            "institution": "Forbes"
                        },

                        "fr": {
                            "title": "Mention d'Article - Contribution UX",
                            "description": "Mis en avant dans Forbes pour d'excellentes contributions UX ; designs et idées impactantes.",
                            "institution": "Forbes"
                        },

                        "zh": {
                            "title": "文章提及 - 用户体验贡献",
                            "description": "在福布斯杂志上因出色的用户体验贡献而受到关注；设计和见解产生了影响。",
                            "institution": "Forbes"
                        }
                    },
                    "links": [
                        {"href": "https://forbes.com", "stringKey": "view_more_info"}
                    ]
                }
            ]
        },