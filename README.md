# Resume_Latex_Code

%-------------------------
% Resume in Latex
% Author : Jake Gutierrez
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://souroabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}

% -------------------- HEADING--------------------
\begin{flushright}
  \vspace{-4pt}

\end{flushright}

\vspace{-5pt}

\noindent
\begin{minipage}[t]{0.1\textwidth}
    \begin{left}
        \vspace{1pt}
        \textbf{\color{white} \Huge \scshape Mr. } 
        \vspace{-10pt}
    \end{left}
\end{minipage}%
\begin{minipage}[t]{0.5\textwidth}
    \begin{flushleft}
        \vspace{-20pt}
        \textbf{\color{Black} \Huge \scshape Pratik Biswas } 
        \vspace{1pt} \\
        \href{https://pratikbiswas-2004.web.app/}{\underline{Visit my Portfolio}}
    \end{flushleft}
\end{minipage}%
\begin{minipage}[t]{0.4\textwidth}
    \begin{flushright}
        \small
        \href{mailto:pratik04biswas@gmail.com}{pratik04biswas@gmail.com} \faIcon{envelope} \\
        \vspace{1pt}
        KOLKATA, INDIA \faIcon{map-marker} \\
        \vspace{1pt}
        \href{https://www.linkedin.com/in/pratik-biswas-511812223/}{linkedin/Pratik Biswas} \faIcon{linkedin} \\
        \vspace{1pt}
        \href{https://github.com/00Pratik-Biswas00}{github/00Pratik-Biswas00} \faIcon{github}
    \end{flushright}
\end{minipage}

% \vspace{10pt}


\vspace{-25pt}



%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Techno Main Salt Lake, Kolkata}{Sep 2021 -- June 2025}
      {Bachelor of Technology in Computer Science and Engineering (AIML)}{Current CGPA - 9.03}
  \resumeSubHeadingListEnd

%------RELEVANT COURSEWORK-------
\section{Relevant Coursework}
    %\resumeSubHeadingListStart
        \begin{multicols}{3}
            \begin{itemize}[itemsep=-5pt, parsep=3pt]
                \item\small Data Structures and Algorithms
                \item  Machine Learning
                \item  Deep Learning
                \item Database Management
                \item  Object-Oriented Programming
                \item Probability and Statistics
            \end{itemize}
        \end{multicols}
        \vspace*{2.0\multicolsep}
    %\resumeSubHeadingListEnd


%-----------EXPERIENCE-----------
\section{Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
  {Celebal Technologies}{May 2024 -- July 2024}
  {React.js Intern}{Remote}
  \resumeItemListStart
    \resumeItem{Implemented a \href{https://github.com/00Pratik-Biswas00/Natyomancha-A_Theatre_Ticket_Booking_Application} {\underline {ticket booking application}} using MERN stack as the final project.}
    \resumeItem{Created a feature-rich Admin dashboard, Spotify clone, and robust E-commerce site, mastering front-end (React) and back-end (Node.js, MongoDB) technologies, and improved code efficiency by 40\% during the internship}
  \resumeItemListEnd



    
  \resumeSubHeadingListEnd
\vspace{-16pt}

%-----------PROJECTS-----------
\section{Projects}
    \vspace{-5pt}
    \resumeSubHeadingListStart
      \resumeProjectHeading
          {\textbf{Chhobimancha} $|$ \emph{React.js, Node.js, Express, MongoDB, Razorpay API}} {\href{https://github.com/sattwikeeg100/Chhobimancha}{\underline{GitHub}} \hspace{0.1em} \href{https://chhobimancha.vercel.app}{\underline{Live Link}} \hspace{0.1em} \href{https://www.youtube.com/watch?v=7M_jV8oXW9Y}{\underline{YT Link}} }
          \resumeItemListStart
            \resumeItem{Designed and developed user interfaces for both user and admin panels, ensuring a seamless and intuitive experience for theatre ticket booking and managing cineastes, shows, etc.}
            \resumeItem{Enhanced more than 25 users' experience with a fully responsive design using Tailwind CSS, and more than 50 contents.}
            \resumeItem{Enabled smooth payment processes using integrated measures, facilitating secure transactions for buying subscriptions and booking live theatre tickets with Razorpay API. }
          \resumeItemListEnd
          \vspace{-13pt}
      \resumeProjectHeading
          {\textbf{Alaap} $|$ \emph{Next.js, Node.js, Express, MongoDB, GraphQL, REST API, Socket.io}}{\href{https://github.com/rupal-draft/Alaap}{\underline{GitHub}} \hspace{0.1em} \href{https://www.youtube.com/watch?v=u51sKAr8gLA}{\underline{YT Link}} }
          \resumeItemListStart
            \resumeItem{Led the UI design and front-end development for Alaap, ensuring a visually appealing and user-friendly interface using React JS and Tailwind CSS.}
            \resumeItem{Alaap enables users to post images, videos, likes and comments and includes a real-time chat feature.}
            
          \resumeItemListEnd 
          \vspace{-13pt}
       \resumeProjectHeading
          {\textbf{Pramā} $|$ \emph{Python, Flask, React.js, Tailwind, APIs (Google Gemini API, etc.)}}{\href{https://github.com/zaibreyaz/Prama}{\underline{GitHub}} \hspace{0.1em} \href{https://youtu.be/L9X9bWrX5W4?si=JyYxJgwH0768_prR}{\underline{YT Link}}}
          \resumeItemListStart
            \resumeItem{Spearheaded the development and design of the frontend and user interface for Pramā, an AI-powered educational platform (summarizing PDFs, generating notes from YouTube videos, a topic-wise test feature, etc.) using Reac.js and Tailwind CSS.}
            \resumeItem{Enhanced platform usability by 25\% through integration of various APIs.}
            \resumeItem{Boosted student engagement and learning outcomes with an interactive chat section and topic-wise test feature.}
          \resumeItemListEnd 
          \vspace{-13pt}
       \resumeProjectHeading
          {\textbf{Re-design Camel} $|$ \emph{React.js, Tailwind CSS, Firebase}}{\href{https://github.com/Chandrima-Kar/DecodiansReimagineRound1}{\underline{GitHub}} \hspace{0.1em} \href{https://re-imagine-camel.web.app/}{\underline{Live Link}} \hspace{0.1em} \href{https://youtu.be/0Blwc1Lbwrw?si=suewFvRUxGu-njIb}{\underline{YT Link}}}
          \resumeItemListStart
            \resumeItem{Led the complete redesign of one of India's oldest art and stationery supplies companies, Camel, using React.js and Tailwind CSS, increasing mobile traffic by 50\% a modern and intuitive user interface.}
            \resumeItem{Improved user engagement and satisfaction by 20\% through interactive content transitions using Swiper.js.}
           
          \resumeItemListEnd 
    \resumeSubHeadingListEnd
\vspace{-15pt}


%------RELEVANT COURSEWORK-------
\section{Technical Skills}
    %\resumeSubHeadingListStart
        \begin{multicols}{5}
            \begin{itemize}[itemsep=-5pt, parsep=3pt]
                \item\small React.js
                \item Node.js
                \item MongoDB
                \item Express.js
                \item Tailwind CSS
                \item HTML/CSS
                \item Javascript
                \item Java
                \item Python
                \item C
                
            \end{itemize}
        \end{multicols}
        \vspace*{1.0\multicolsep}
    %\resumeSubHeadingListEnd

    
%
%-----------PROGRAMMING SKILLS-----------
\section{Additional Information}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Technologies and Tools}{: GitHub, VS Code, Google Cloud Platform} \\
     \textbf{Languages}{: English, Hindi, Bengali} \\
     \textbf{Activities}{: Got 1st place in the Tech-AI Hackathon - 2024, Participated in \href{https://www.linkedin.com/posts/pratik-biswas-511812223_hack4bengal-innovation-creativity-activity-7215002504646774784-PGe9?utm_source=share&utm_medium=member_desktop}{\underline{Hack4bengal3.0 - 2024}}, Participated in \href{https://www.linkedin.com/posts/pratik-biswas-511812223_webdesign-reimaginecontest-sheryianscodingschool-activity-7213908721947541504-CV_g?utm_source=share&utm_medium=member_desktop}{\underline{Sheryians Re-imagine Hackathon - 2024}}} \\
     \textbf{Achievements}{: 4-star in Java, 4-star in C, 3-star in Python on \href{https://www.hackerrank.com/profile/04biswaspratik}{\underline{Hackerrank}}, 2-star in \href{https://www.codechef.com/users/pratik_biswas}{\underline{CodeChef}}, 80+ questions solved in \href{https://leetcode.com/u/Pratik_Biswas/}{\underline{LeetCode}} } \\
     \textbf{Certificates}{: {\href{https://www.linkedin.com/in/pratik-biswas-511812223/details/certifications/1716697727566/single-media-viewer/?type=DOCUMENT&profileId=ACoAADgu8V0Bo4ckfCXTMUUyb4e9naHsCHqwRV4}{\underline{IBM - Getting Started with Enterprise-grade AI}}, \hspace{0.1em} \href{https://www.linkedin.com/in/pratik-biswas-511812223/details/certifications/1716697638391/single-media-viewer/?type=DOCUMENT&profileId=ACoAADgu8V0Bo4ckfCXTMUUyb4e9naHsCHqwRV4}{\underline{IBM - Journey to Cloud: Envisioning Your Solution}}}} \\

    }}
 \end{itemize}
 \vspace{-16pt}





\end{document}
