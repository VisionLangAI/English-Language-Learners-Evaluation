# English-Language-Learners-Evaluation Dataset

## Overview
This dataset contains 6,482 entries, each representing an English language learner's essay submission along with detailed evaluation and learner profile features. The dataset is designed for research on automated language learner assessment, feature ranking, and AI-driven evaluation systems.

## Columns Description

### Original Attributes
- **text_id**: Unique identifier for each essay.
- **full_text**: The essay text submitted by the learner.
- **grade**: Academic grade or level of the student.
- **prompt**: The essay prompt or topic.
- **Overall**: Overall score for the essay.
- **Cohesion**: Score for textual cohesion.
- **Syntax**: Syntactic quality score.
- **Vocabulary**: Vocabulary usage score.
- **Phraseology**: Score for phrase usage and originality.
- **Grammar**: Grammatical accuracy score.
- **Conventions**: Score for spelling, punctuation, and writing conventions.

### Added Contextual & Demographic Features
- **age_group**: Learner's age bracket. Categories: `18-24`, `25-35`, `36-50`.
- **native_language**: Primary language spoken by the learner. E.g., `English`, `Spanish`, `Chinese`, `Urdu`, `Arabic`, `Other`.
- **learning_environment**: Type of learning environment. E.g., `public_school`, `private_school`, `online`, `homeschooling`.
- **prior_experience**: Level of prior English learning experience. E.g., `beginner`, `intermediate`, `advanced`.

### Added Psycholinguistic & Cognitive Features
- **attention_span_score**: Attention span score, integer scale from 1 (low) to 5 (high).
- **working_memory_index**: Working memory index, integer scale from 1 (low) to 5 (high).
- **motivation_level**: Overall learner motivation. Categories: `low`, `medium`, `high`.
- **cognitive_load**: Cognitive load experienced by the learner during the task. Categories: `low`, `medium`, `high`.

## Usage
This dataset can be used for machine learning model training, feature ranking analysis, explainable AI research, and studies involving the integration of linguistic, demographic, and cognitive factors in automated learner evaluation systems.

## File Information
- **Filename:** `ELA_Dataset.csv`
- **Number of Entries:** 6,482
- **Number of Columns:** 19

