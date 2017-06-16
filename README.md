# HTML Slide Deck for EDRi

The live version of this template is available [here](http://www.privacypies.org/edri-slide-deck-template/talk_name).

# Instructions
### Step 1: Making your slides available on www.edri.org/your_name_talks/
1. Create a folder in **your name** in EDRi's server using FTP access (using Filezilla). 
2. Download this repository and upload all its content to the folder to EDRi's site that you created in the previous step using FTP/FileZilla.
3. When you visit www.edri.org/your_name_talks/ or www.edri.org/your_name_talks/index.html you will see a page, where you can put your bio, list all your talks chronologically. Update your bio first by editing the index.html file.
4. Remember, Step 1 is done only for the first time.

### Step 2: Creating slides using this template
1. Everytime you have to create a folder, come to this repository (online folder) and download it on your computer.
2. Now, copy the folder called **talk_name** and rename it with a nice name to it (e.g. CPDP17). When everything is done, your slides will be available on www.edri.org/your_name_talks/CPDP17 . So, name the folder wisely.
3. Inside the talk_name folder, there is a file called *index.html* which is the slide.
4. Open it up in a browser, as well as it gedit (or any ascii text editor).
5. Imagine, you want to create a slide  with bullet points, the corresponding code block is as follows:
```html
<div id="list" class="slide"><div>
    <section>
      <header>
        <h2>Unordered List</h2>
      </header>
      <ul>
        <li>Tigers</li>
        <li>Elephants</li>
        <li>Bears
          <ul>
            <li>Koalas</li>
            <li>Polar</li>
            <li>Panda</li>
          </ul>
        </li>
        <li>Oh my&hellip;</li>
      </ul>
      <footer class="notes">
      </footer>
    </section>
</div></div>
```

6. If you have to repeat this, copy paste it again, but change <div id="list" class="slide"><div> to something like <div id="list2" class="slide"><div>, and so on.

7. Every slide is contained within the **code block** as follows:
```html
<div id="list" class="slide"><div>
  <section>
	................................
	................................
	................................
     <footer class="notes">
    </footer>
  </section>
</div></div>```

8. So create a new slide, just copy the whole **code block** of your choice.
9. Put all the images into **images** folder.
10. Edit the index.html file outside the CPDP17 folder, and add the title, event, location, etc. Make sure everything works fine on your computer.
11. Once you are OK with the look and feel of the slides, you are ready to put it to EDRi's site.
12. But this time, all you will upload is the newly added images to the images folder in EDRi's site, and the newly created folder (as a whole), index.html folder only.
13. If you have created everything correctly, when you visit www.edri.org/your_name_talks/CPDP17, your slides will be online. Also, when you visit www.edri.org/your_name_talks/ you will see a new entry to CPDP17, and when you click it, it will take you to your slides.




