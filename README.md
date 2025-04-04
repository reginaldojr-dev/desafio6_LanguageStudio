# desafio6_LanguageStudio

## Exemplo de Saída de análise

<pre>
<code>
{
    "documents": [
        {
            "id": "id__3699",
            "sentiment": "mixed",
            "confidenceScores": {
                "positive": 0.13,
                "neutral": 0.14,
                "negative": 0.73
            },
            "sentences": [
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0.02,
                        "neutral": 0.03,
                        "negative": 0.95
                    },
                    "offset": 0,
                    "length": 111,
                    "text": "Although today started with a beautiful sunrise and a sense of hope, things quickly took a turn for the worse. ",
                    "targets": [
                        {
                            "sentiment": "positive",
                            "confidenceScores": {
                                "positive": 0.99,
                                "negative": 0.01
                            },
                            "offset": 40,
                            "length": 7,
                            "text": "sunrise",
                            "relations": [
                                {
                                    "relationType": "assessment",
                                    "ref": "#/documents/0/sentences/0/assessments/0"
                                }
                            ]
                        }
                    ],
                    "assessments": [
                        {
                            "sentiment": "positive",
                            "confidenceScores": {
                                "positive": 0.99,
                                "negative": 0.01
                            },
                            "offset": 30,
                            "length": 9,
                            "text": "beautiful",
                            "isNegated": false
                        }
                    ]
                },
                {
                    "sentiment": "neutral",
                    "confidenceScores": {
                        "positive": 0.07,
                        "neutral": 0.73,
                        "negative": 0.21
                    },
                    "offset": 111,
                    "length": 131,
                    "text": "I was excited about a big presentation at work, something I had spent weeks preparing for, but everything that could go wrong did. ",
                    "targets": [
                        {
                            "sentiment": "positive",
                            "confidenceScores": {
                                "positive": 1,
                                "negative": 0
                            },
                            "offset": 137,
                            "length": 12,
                            "text": "presentation",
                            "relations": [
                                {
                                    "relationType": "assessment",
                                    "ref": "#/documents/0/sentences/1/assessments/0"
                                }
                            ]
                        }
                    ],
                    "assessments": [
                        {
                            "sentiment": "positive",
                            "confidenceScores": {
                                "positive": 1,
                                "negative": 0
                            },
                            "offset": 117,
                            "length": 7,
                            "text": "excited",
                            "isNegated": false
                        }
                    ]
                },
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0,
                        "negative": 1
                    },
                    "offset": 242,
                    "length": 112,
                    "text": "The slides wouldn’t load properly, my voice was shaky, and I could see the disappointment in my manager’s face. ",
                    "targets": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.01,
                                "negative": 0.99
                            },
                            "offset": 280,
                            "length": 5,
                            "text": "voice",
                            "relations": [
                                {
                                    "relationType": "assessment",
                                    "ref": "#/documents/0/sentences/2/assessments/0"
                                }
                            ]
                        }
                    ],
                    "assessments": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.01,
                                "negative": 0.99
                            },
                            "offset": 290,
                            "length": 5,
                            "text": "shaky",
                            "isNegated": false
                        }
                    ]
                },
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0.01,
                        "negative": 0.98
                    },
                    "offset": 354,
                    "length": 99,
                    "text": "It felt like all my efforts had been for nothing, and I couldn’t shake off the feeling of failure. ",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "positive",
                    "confidenceScores": {
                        "positive": 0.58,
                        "neutral": 0.39,
                        "negative": 0.03
                    },
                    "offset": 453,
                    "length": 151,
                    "text": "On the way home, though, a kind stranger helped me pick up some papers I had dropped, and their simple smile reminded me that not everything was lost. ",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0.07,
                        "neutral": 0.25,
                        "negative": 0.68
                    },
                    "offset": 604,
                    "length": 114,
                    "text": "I know I’ll have better days, but right now, I just feel tired, a bit defeated, and in need of some encouragement.",
                    "targets": [],
                    "assessments": []
                }
            ],
            "warnings": []
        }
    ],
    "errors": [],
    "modelVersion": "2025-01-01"
}
</code>
</pre>
