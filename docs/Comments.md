### Composiciones Generales. 

### Datos Anteriores. 

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
        "es": 
        {
            "title": "*Portafolio* Personal",
            "title_short": null,
            "description": "Explora una selección de mis proyectos desarrollados.",
            "nav_label": "Portafolio"
        }
    }
}

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
}

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

### Otros.