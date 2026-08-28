{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Multiplayer Game \'97 Codaisseur Capstone (2019)\
\
Final capstone project for the Codaisseur Full Stack Developer program, co-developed with Matias Mateu.\
\
## Overview\
\
[SUBSTITUTE: brief description of the actual core gameplay loop \'97 two-player, with a flag/goal-based objective and platform mechanics based on the file structure, but confirm the real loop here rather than relying on my guess]\
\
## Tech Stack\
\
**Client** \'97 React, Redux, Socket.IO client\
**Server** \'97 Node.js, Socket.IO server\
\
Real-time client-server state sync (player positions, game state, connection handling) implemented via Socket.IO over WebSocket transport.\
\
## Structure\
\
- `/client` \'97 React/Redux frontend, real-time game state and rendering\
- `/server` \'97 Node.js server, Socket.IO connection handling and game logic\
\
## Context\
\
This project predates Dvor, the falling-block puzzle game currently in development at Studio Betonika, and shares no code with it. It's included here as evidence of hands-on real-time multiplayer architecture experience \'97 Socket.IO/WebSocket communication, shared game state across clients \'97 built prior to and informing Dvor's own Firebase-backed cross-platform leaderboard system.\
\
Built in 2019, unmodified since except for repository reorganisation.}