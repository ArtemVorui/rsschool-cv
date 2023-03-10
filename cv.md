## Vorui Artem

#### Contacts:

- **email:** artemvoruy@gmail.com

- **telegram:** [@XTOCb90](https://t.me/XTOCb90)

- **discord:** [XTOCb#9928](https://discord.com/channels/@me)

- **linkedin:** [Vorui Artem](https://www.linkedin.com/in/artem-vorui/)

#### About myself:
I am organized, decent, responsible and friendly, I know how to communicate with people. 
I have solid computer skills, basic knowledge of website development based on the JavaScript 
programming language, and use the necessary tools for this. 
Very motivated to learn something new and deepen his knowledge. 
I also have enough free time to fully immerse myself in the educational process. 
For my part, I promise to take a responsible attitude to studies, 
to complete all assigned tasks and not to miss classes. 
I have long dreamed of changing my major and becoming a professional web developer. 
I spend my free time learning different technologies and tools for website development. 
This project is extremely important for me, it will help me learn something new, 
systematize my knowledge, gain practical skills, give me the opportunity 
to communicate with like-minded people, learn from the experience of professional mentors, 
raise the level of my knowledge to a new level, learn about approaches in the development 
of web applications, will create a number of projects for my portfolio and in the end 
will give me the opportunity to receive an invitation to work in an international company.

#### Skills:
- HTML
- CSS(SASS)
- Bootstrap
- JavaScript
- React
- Webpack
- BEM
- Git
- NodeJS

#### Code example:
````
import s from './Progress.module.scss';
import {useState, useEffect} from 'react';
import ProgressBar from 'react-bootstrap/ProgressBar';

const Progress = () => {
    const [progress, setProgress] = useState(0);

    useEffect(() => {
        const onScroll = () => {
            const scrollTop = document.documentElement.scrollTop;
            const windowHeight = window.innerHeight;
            const fullHeight = document.documentElement.scrollHeight;
            const scrolled = scrollTop / (fullHeight - windowHeight) * 100;
            setProgress(scrolled);
        };

        window.addEventListener('scroll', onScroll);

        return () => {
            window.removeEventListener('scroll', onScroll);
        };
    }, []);

    return (
        <>
            <ProgressBar className={s.progress} now={progress}/>
        </>
    );
}

export default Progress;
````

#### Experience:
The final project of one of the courses I recently completed (React, SASS, Bootstrap): 
[here](https://github.com/ArtemVorui/decbase)

#### Education:
- Chernihiv national Pedagogical University name after T.H.Shevchenko, 
Institute of history, ethnology and jurisprudence name after O.M.Lazarevskogo - 
Specialized degree in history and law (September 2007 - June 2012)

- First Chernihiv foreign language courses, Chernihiv (2015 - 6 months)

- “Front-end development”, Beetroot academy, Chernihiv (2018 - 4 months)

- English classes, Beetroot academy, Chernihiv (2018 - 4 months)

- “Advanced JavaScript”, Beetroot academy, Chernihiv (2018 - 2 months)

- Private english classes, Chernihiv (April 2019 - July 2019)

- “Front-end development”, Sigma Software Univesity (October 2022 - February 2023)

#### Languages:
- English (B1)

- Ukrainian (native)

- Russian (fluent)