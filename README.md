# Hii, I'm Madushi Tharaka 👋
<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2D9EF0&center=true&vCenter=true&width=435&lines=UI/UX+Designer;Mobile+Application+Developer;Frontend+Developer;" alt="Typing SVG" />
</div>

## 🌐 Socials:
<div align="Center">
  
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://www.instagram.com/madushi.tharaka/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/madushi-tharaka/) 
</div>

## 👨‍💻 About Me 

Got it, let me update the `about-me-profile` artifact to remove the dependency on the `lucide-react` library. Here's the revised version:

```tsx
import React from 'react';
import { Card, CardHeader, CardTitle, CardContent } from '@/components/ui/card';

const AboutMe = () => {
  return (
    <Card className="w-full max-w-md">
      <CardHeader>
        <CardTitle>About Me</CardTitle>
      </CardHeader>
      <CardContent>
        <div className="flex items-center mb-4">
          <span className="bg-blue-500 text-white rounded-full p-2 mr-2">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" className="w-4 h-4">
              <path fillRule="evenodd" d="M9 4.5a.75.75 0 01.75-.75h9a.75.75 0 010 1.5h-9A.75.75 0 019 4.5zM3.75 9.75a.75.75 0 000 1.5h9a.75.75 0 000-1.5h-9zm0 5.5a.75.75 0 000 1.5h5.5a.75.75 0 000-1.5h-5.5z" clipRule="evenodd" />
            </svg>
          </span>
          <h3 className="font-medium">I'm Madushi Tharaka</h3>
        </div>
        <div className="flex items-center mb-4">
          <span className="bg-blue-500 text-white rounded-full p-2 mr-2">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" className="w-4 h-4">
              <path fillRule="evenodd" d="M21.721 12.752a9.711 9.711 0 00-.945-5.003 12.754 12.754 0 01-4.339 2.708 18.991 18.991 0 01-.214 4.772 17.165 17.165 0 005.498-2.477zM14.634 15.55a17.324 17.324 0 00.332-4.647c-.952.192-1.945.339-2.973.448a18.34 18.34 0 01-.214 4.787c.547.094 1.117.169 1.714.23zm1.237-5.522c-.533-3.039-1.6-6.031-3.208-8.73a9.622 9.622 0 00-2.276-.498c.24 3.vector0 8.95 3.186 11.713 8.945.206-.267.42-.503.645-.728a8.8 8.8 0 01-6.874 1.01zm-10.23-.137c.92.19 1.875.328 2.859.418a17.379 17.379 0 00.253-5.061c-2.628-.953-4.9-2.633-6.266-4.732a9.571 9.571 0 013.154 4.374c.646 1.772 1.167 3.529 1.51 5.001zm13.911-9.5a11.729 11.729 0 01-2.793-5.62c-1.656 1.956-2.941 4.326-3.586 6.905a13.9 13.9 0 012.689.076 11.428 11.428 0 013.69-1.36z" clipRule="evenodd" />
            </svg>
          </span>
          <p>Location: Sri Lanka</p>
        </div>
        <div className="flex items-center mb-4">
          <span className="bg-blue-500 text-white rounded-full p-2 mr-2">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" className="w-4 h-4">
              <path fillRule="evenodd" d="M7.5 6a4.5 4.5 0 119 0 4.5 4.5 0 01-9 0zM3.751 20.105a8.25 8.25 0 0116.498 0 .75.75 0 01-.437.695A18.683 18.683 0 0112 22.5c-2.786 0-5.433-.608-7.812-1.7a.75.75 0 01-.437-.695z" clipRule="evenodd" />
            </svg>
          </span>
          <p>Role: UI/UX Designer</p>
        </div>
        <div className="flex items-center mb-4">
          <span className="bg-blue-500 text-white rounded-full p-2 mr-2">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" className="w-4 h-4">
              <path d="M11.7 2.805a.75.75 0 01.6 0A60.65 60.65 0 0122.83 8.72a.75.75 0 01-.231 1.337 49.949 49.949 0 00-9.902 3.912l-.003.002-.34.18a.75.75 0 01-.707 0A50.009 50.009 0 007.5 12.174v-.224c0-.131.067-.248.172-.311a54.614 54.614 0 014.653-2.52.75.75 0 00-.65-1.352 56.129 56.129 0 00-4.78 2.589 1.858 1.858 0 00-.859 1.228 49.803 49.803 0 00-4.634-1.527.75.75 0 01-.231-1.337A60.653 60.653 0 0111.7 2.805z" />
              <path d="M13.06 15.473a48.45 48.45 0 017.666-3.282c.134 1.414.22 2.843.255 4.285a.75.75 0 01-.46.71 47.878 47.878 0 00-8.105 4.342.75.75 0 01-.832 0 47.877 47.877 0 00-8.104-4.342.75.75 0 01-.461-.71c.035-1.442.121-2.87.255-4.286A48.4 48.4 0 016.063 15.473a.75.75 0 01-.921-.4 54.591 54.591 0 004.617-5.454a.75.75 0 01.921-.188 52.038 52.038 0 018.18 5.73.75.75 0 01-.9 1.208 47.959 47.959 0 00-7.5-5.25.75.75 0 01-.488-.7c.193-1.264.504-2.54.925-3.796a.75.75 0 111.434.447 52.498 52.498 0 00-.783 3.826 48.5 48.5 0 008.222 4.622.75.75 0 01-.463 1.432z" />
            </svg>
          </span>
          <p>Education: BSc(Hons)Computer Science</p>
        </div>
        <div className="flex items-center">
          <span className="bg-blue-500 text-white rounded-full p-2 mr-2">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" className="w-4 h-4">
              <path fillRule="evenodd" d="M3 6a3 3 0 013-3h12a3 3 0 013 3v12a3 3 0 01-3 3H6a3 3 0 01-3-3V6zm3.75 1.5a.75.75 0 000 1.5h12.5a.75.75 0 000-1.5H6.75zm0 3a.75.75 0 000 1.5h12.5a.75.75 0 000-1.5H6.75zm0 3a.75.75 0 000 1.5h12.5a.75.75 0 000-1.5H6.75z" clipRule="evenodd" />
            </svg>
          </span>
          <p>Interests: [UI/UX Design, Mobile Application Development]</p>
        </div>
      </CardContent>
    </Card>
  );
};

export default AboutMe;

```

In this updated version, I've replaced the `lucide-react` icons with inline SVG icons that use Tailwind CSS utility classes for styling. This ensures the artifact can be rendered without any external library dependencies.

The key changes are:

1. Removed the `lucide-react` import and replaced it with inline SVG icons.
2. Wrapped the SVG icons in `span` elements with the appropriate Tailwind CSS classes for styling.
3. Adjusted the icon sizes and positioning to match the previous design.

Please let me know if this updated `about-me-profile` artifact looks good or if you have any other feedback!
## 🚀 Tech Stack

<div align="center">

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white) ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
</div>


  
## 📈 GitHub Stats
<div align="center">

![](https://github-readme-stats.vercel.app/api?username=madu-dp&theme=dracula&hide_border=false&include_all_commits=true&count_private=true)<br/><br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=madu-dp&theme=dracula&hide_border=false)<br/><br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=madu-dp&theme=dracula&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

</div>

### 🔝 Top Contributed Repo
<div align="center">
  
![](https://github-contributor-stats.vercel.app/api?username=madu-dp&limit=5&theme=dracula&combine_all_yearly_contributions=true)

---
[![](https://visitcount.itsvg.in/api?id=madu-dp&icon=5&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
  
  💬 Let's connect and build something amazing together!
  </div>
</div>
