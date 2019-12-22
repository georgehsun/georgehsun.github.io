# George_Sun_Portfolio

ReadMe


included: contact.html, contact.css, index.html, index.css, portfolio.html, portfolio.css, assets file, image file.

Homework #2

This homework was for my contact, index, and portfolio about me. If you click on any of the links on the top right hand corner, you will see that all pages are responsive. If you minimize the page, you will also notice that everything in it will also shrink or expand. 

One of the biggest thing that was giving me trouble was the foote. If I was to minimize the page, the footer never aligned with my page. So I did the code down below and it fxed my problem.


# html...
<footer class="footer">
    <p>Copyright</p>
    </footer> 

# css...

    .footer{

    left: 0;
    bottom: 0;
    width: 100%;
    background-color: #666666;
    color: white;
    height: 2rem;
    border-top: 8px solid #4aaaa5;
    text-align: center;
        position: fixed;
     
    }


On the homework #1 I didn't provide a href on my nav bar, so I fixed that. Now everytime you click on about, contact, or portfolio it will send you to the appropriate link.
