// Clone it
git clone https://github.com/haloriyan/meme.js

// Attach library
<script src="meme.js"></script>

// Example of use
let meme = new MemeJS({
    width: 600,
    height: 600
})
meme.setTemplate("./assets/bg.jpg")
meme.addImage({
    src: './assets/js.jpg',
    width: 130,
    height: 130,
    position: {
        x: 200,
        y: 305
    }
})
meme.addText({
    text: '*temen: lu kalo bikin meme gimana?',
    position: {
        x: 25, 
        y: 55
    }
})
meme.addText({
    text: 'gw :',
    position: {
        x: 25, 
        y: 105
    }
})
