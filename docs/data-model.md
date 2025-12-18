# Datamodell – Hjernens 5 om dagen

## User
- id
- created_at
- timezone
- level
- consistency_score

## Word
- id
- word
- difficulty
- category
- explanation_base
- example_base

## Session
- id
- user_id
- date
- completed

## Question
- id
- session_id
- word_id
- position

## Attempt
- id
- question_id
- selected_option
- is_correct
- response_time_ms

## Review
- user_id
- word_id
- next_review_date
- strength_score

## WeeklySummary
- user_id
- week_start
- correct_rate
- strongest_categories
- weakest_categories
- ai_commentary
