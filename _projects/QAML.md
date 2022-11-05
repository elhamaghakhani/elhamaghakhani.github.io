---
layout: page
title: QAML - Trivia Question writing Aided by Machine Learning
description: Human in the loop adversarial question writing
img: assets/img/qaml_teaser.png
importance: 2
category: Academic
---

<p style='text-align: justify;'>Questions in Trivia games span a wide variety of Academic Topics and Difficulty Levels. Writing of such questions requires intricate knowledge of the existing questions, format of the game and difficulty levels with respect to the target audience. This works presents QAML: Question Authoring Aided by Machine Learning, an interactive website meant to help authors write difficult, diverse and interpretable questions for a popular Trivia Game named Quizbowl. We envision this interface to be the 'Go-To' website for all quiz bowl authors. QAML has a suite of interactive machine-learning tools working in real time in a widget-based design. The interface assist users in improving question diversity by recommending relevant yet underrepresented topics, and identifying similar phrases from past questions. The interface uses previous school and university competition questions along with large scale language models to determine the difficulty of questions in real time. It also hosts a set of features made for wholesome user experience such as determination of difficult to pronounce words, highlighting of the text using radiant colors, and the ability to download questions for future practice. Furthermore, the interface meets the requirements of the modern world, where AI Agents are able to compete and often beat their Human counter parts, and provides ways to write adversarial questions for AI Agents. This interactivity combines the robustness of machine models with the ingenuity of human creativity and makes question-answering an exciting community for all.</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/qaml_img.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A snapshot of the Question Authoring interface.
</div>

<p style='text-align: justify;'>Quizbowl is a popular buzzer-based trivia competition where players or teams of players play to answer questions before other teams with the end goal of obtaining a higher score. A moderator reads the question and players or teams of players try to answer correctly for points, by beating other teams on the buzzer. The answers of the questions are well-known entities, but cover a wide range of academic topics like Science, Fine Arts, Literature, History etc. This game format means that a player can buzz in before the question is completed. Therefore question authors are often tasked with three objectives:</p>
- The first objective is to create questions such that people who know about the answer are able to buzz quicker. This is to prevent a Jeopardy! like game, where often more knowledgeable players are unable to answer due to losing out on the lockout buzzer.
- The second objective is to create questions that can be solved. This is to ensure that the game play remains interesting and exciting.
- With AI Agents performing at par or better than Humans in popular games, the third objective requires authors to write Adversarial questions that are difficult for AI agents.

<p style='text-align: justify;'>Meeting all of these objectives is a difficult task. This requires trivia authors to write inverse pyramidal questions, where the first phrase/sentence contains the most difficult clue to guess the answer and the last phrase/sentence contains a giveaway clue that is usually known by many. Due to this specific format, authoring of questions is usually done by experienced ex-players and not by novice authors. Our interactivity fills this gap through a game-like widget based-interface which provides the tools a novice or a professional author may require. This interactivity contains tools which fall into three broad categories:</p>
* Ensuring Competitive Questions 
* Injecting Diversity into game play 
* Making Question Authoring Easier through features suggested by experienced authors and moderators

<p style='text-align: justify;'>Our project work demonstrates how a user may use this platform for writing quality trivia questions. It extends previous ideas of adversarial question answering on Quizbowl and adds more widgets for diversity of questions, interpretability of machine learning models, interactive features such as highlighting, and a sleeker minimalist UI. We describe a new mechanisms using which humans and computer collaborate to write questions. Thereafter, we present details on how our widget based design is implemented and show how large language models can be used for our task.</p>
