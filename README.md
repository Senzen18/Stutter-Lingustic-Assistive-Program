# Stutter Linguistic Assistance Program

•Created an AI based app to assist people with childhood
onset fluency disorder(Stuttering) which provides
synonyms for words that are difficult to pronounce for
that specific user.

•It uses Active Learning for training and is able to achieve
80% accuracy for suggesting alternates in 50-60 user
interactions

# Overview
Stuttering is a speech disorder that affects millions of people globally, significantly influencing both their personal and professional lives. To avoid the stigma and embarrassment associated with stuttering, individuals who stutter (PWS) often use various strategies to conceal their condition. A common approach is word substitution, where a person avoids a potentially challenging word and replaces it with an alternative. However, research indicates that this practice can increase stress and impose an additional mental burden.

In this work, we introduce SLAP, an AI-powered writing assistant designed to help PWS craft scripts they can deliver fluently. SLAP employs an innovative active learning approach to identify words that may be difficult for the user to pronounce. These words are highlighted in the tool's interface, and when hovered over, SLAP suggests alternative words with similar meanings that are easier to articulate. Users have the flexibility to either accept or dismiss these suggestions. Over time, SLAP adapts to each user's preferences and speech patterns through their feedback, continuously refining its recommendations to better address their individual needs.

Through a simulation study, we demonstrate SLAP's ability to effectively learn and adapt to a user's unique requirements. This tool can be particularly valuable in high-stakes scenarios such as public speaking, presentations, and other important events.

## Installation Instructions

- Clone this repo

- Install Dependencies using: pip install -r req.txt

- python -m spacy download en_core_web_sm

- Run python app.py

- Browse localhost:3999
