KodlaSınav Studio

A content production tool that automatically turns questions from a question bank into short social media videos.

KodlaSınav Studio is an automation app that turns text-based multiple-choice questions into vertical videos ready to post. It takes a question, places it in a design template, and exports it as an MP4 with the answer and an explanation.

Someone who shares educational content has to do the same steps for every question: open the design, place the text, prepare the answer screen, export the video and write the post caption. That's easy for one question, but with hundreds of questions it becomes repetitive work.

Main goal: Remove this repetition. The user focuses on whether the content is correct, and the app takes care of design, video production and getting posts ready to publish. This means:

Hundreds of questions become videos with a single click.
All videos share the same design language.
Students can review with short videos while scrolling.
How does it work?
Select: Choose a topic from the question bank.
Review: Check and edit the question in a live preview.
Generate: The system draws the question and answer cards and turns them into a video.
What's under the hood?
React + Vite: admin panel and question editor
Node.js + Express: API that manages production jobs
Python + Pillow: card rendering that sizes itself to fit the text
FFmpeg: video creation
Remotion + Edge TTS: option for videos with voiceover
Metricool API: post scheduling
