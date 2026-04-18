interview-intelligence/
│
├── app/
│
│   ├── main.py
│
│   ├── config/
│   │   ├── settings.py
│   │   ├── database.py
│   │   └── redis.py
│
│   ├── api/
│   │   ├── deps.py
│   │
│   │   └── routes/
│   │       ├── auth.py
│   │       ├── interview.py
│   │       ├── analysis.py
│   │       ├── feedback.py
│   │       └── dashboard.py
│
│   ├── schemas/
│   │   ├── user_schema.py
│   │   ├── interview_schema.py
│   │   ├── analysis_schema.py
│   │   ├── feedback_schema.py
│   │   ├── score_schema.py
│   │   └── resume_schema.py
│
│   ├── models/
│   │   ├── user.py
│   │   ├── interview.py
│   │   ├── question.py
│   │   ├── answer.py
│   │   ├── signal.py
│   │   ├── emotion.py
│   │   ├── score.py
│   │   ├── decision.py
│   │   ├── feedback.py
│   │   └── resume.py
│
│   ├── repository/
│   │   ├── user_repo.py
│   │   ├── interview_repo.py
│   │   ├── analysis_repo.py
│   │   ├── feedback_repo.py
│   │   └── resume_repo.py
│
│   ├── services/
│   │
│   │   ├── interview_service.py
│   │   ├── transcription_service.py
│   │   ├── signal_service.py
│   │   ├── vision_service.py
│   │   ├── evaluation_service.py
│   │   ├── ideal_answer_service.py
│   │   ├── comparison_service.py
│   │   ├── resume_service.py
│   │   ├── scoring_service.py
│   │   ├── decision_service.py
│   │   ├── feedback_service.py
│   │   ├── improvement_service.py
│   │   └── email_service.py
│
│   ├── ai/
│   │
│   │   ├── gemini_engine.py
│   │   ├── prompt_builder.py
│   │   ├── response_parser.py
│   │
│   │   ├── pipelines/
│   │   │
│   │   │   ├── answer_pipeline.py
│   │   │   ├── technical_pipeline.py
│   │   │   ├── behavioral_pipeline.py
│   │   │   ├── communication_pipeline.py
│   │   │   ├── ideal_answer_pipeline.py
│   │   │   ├── comparison_pipeline.py
│   │   │   ├── resume_match_pipeline.py
│   │   │   └── decision_pipeline.py
│   │
│   │   └── evaluators/
│   │       ├── answer_evaluator.py
│   │       ├── technical_evaluator.py
│   │       ├── behavioral_evaluator.py
│   │       └── communication_evaluator.py
│
│   ├── core/
│   │   ├── orchestrator.py
│   │   └── pipeline.py
│
│   ├── workers/
│   │   ├── celery_app.py
│   │
│   │   └── tasks/
│   │       ├── transcription_task.py
│   │       ├── signal_task.py
│   │       ├── vision_task.py
│   │       ├── analysis_task.py
│   │       ├── comparison_task.py
│   │       ├── feedback_task.py
│   │       └── email_task.py
│
│   ├── patterns/
│   │   ├── pattern_engine.py
│   │   ├── weakness_detector.py
│   │   └── trend_analyzer.py
│
│   ├── storage/
│   │   ├── s3_client.py
│   │   └── file_manager.py
│
│   ├── utils/
│   │   ├── audio_utils.py
│   │   ├── video_utils.py
│   │   ├── text_utils.py
│   │   ├── metrics_utils.py
│   │   ├── resume_utils.py
│   │   └── logger.py
│
│   └── tests/
│       ├── test_pipeline.py
│       ├── test_analysis.py
│       ├── test_feedback.py
│       └── test_decision.py
│
├── requirements.txt
├── docker-compose.yml
└── README.md