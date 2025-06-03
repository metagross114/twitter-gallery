
# Twitter Gallery Project License Selection and Explanation

**Project Name:** Twitter Gallery  
**GitHub Repository:** [https://github.com/emrecoban/twitter-gallery](https://github.com/emrecoban/twitter-gallery)



### 1.  Project Purpose and Scope
(In the past) Twitter's media tab was quite useless. To solve this, I developed a grid system similar to the Instagram view. It doesn't work properly now. Because Twitter updated the media tab after I develop this project.

### 2.  License Options and Evaluation
As the project developer, I evaluated the following licenses:

1.  **MIT License**
    
    -   **Advantages:**
        
        -   Very few restrictions; users can copy, modify, and use the project for commercial purposes.
            
        -   Simple and concise text that anyone can easily understand.
            
    -   **Disadvantages:**
        
        -   Users of the project are not required to share their modifications. In other words, there is no copyleft provision requiring source sharing.
            
2.  **Apache License 2.0**
    
    -   **Advantages:**
        
        -   Provides most of the permissions that the MIT License does.
            
        -   Includes a “patent grant” clause, which can be useful if the project later integrates patented technology.
            
    -   **Disadvantages:**
        
        -   Longer and more technical than the MIT License.
            
        -   Patent protection may not be necessary for a simple personal or academic project.
            
3.  **GNU GPL v3**
    
    -   **Advantages:**
        
        -   Under the copyleft principle, anyone who receives the code (including derivative projects) must distribute it under the same license.
            
        -   Prevents the code from being closed source or turned into a proprietary version.
            
    -   **Disadvantages:**
        
        -   It is difficult to integrate into commercial applications or include in other closed-source projects. The requirement that “anyone who uses it must also be open source” can deter some organizations from contributing.
         

### 4.  Chosen License: MIT License
I chose the **MIT License** for Twitter Gallery. My reasons are:

-   **Community Contribution and Sustainability:** I want to encourage code sharing. With MIT, the “copy, enhance, share” philosophy keeps doors open for everyone. Therefore, when others want to contribute to the project, the lack of restrictive clauses is encouraging.
    
-   **No Need for Patent Protection:** There is currently no plan to focus on patented technology or integrate any patent-protected features. Therefore, the additional patent protection offered by Apache 2.0 is not necessary.
    
-   **Short and Understandable:** Having a license text that is short, straightforward, and easily readable prevents confusion when sharing the software.
    
### 4.  How the License was Added to the Repository
In the `twitter-gallery` repository on GitHub, I followed these steps:

1.  On the repository’s main page, I clicked “Add file → Create new file” and created a file named `LICENSE`.
    
2.  From the “Choose a license template” menu, I selected “MIT License.” In the automatically generated template, I updated the year and author name as needed.
    
3.  I clicked “Commit new file” to save it.
    

Below is the full content of the **LICENSE** file as it appears in the repository:

```text
MIT License

Copyright (c) 2023 Emre COBAN

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```

----------

This page was prepared by emrecoban for the training activity of Desarrollo de software libre.
