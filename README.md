# photo-showcase
An HTML photo showcase page with proper alt text, figures with captions, and an embedded video.

# Key aspects of this project
- **A semantic page**: Use <code>&lt;header&gt;</code>, 
<code>&lt;main&gt;</code>, and <code>&lt;footer&gt;</code> to structure the page itself.
- **At least six images** inside the main content. Each <code>&lt;img&gt;</code> must include:
    - A <code>src</code> that points to a real image (a local file or a public URL).
    - A useful <code>alt</code> attribute that describes the image, not the filename.
    - <code>width</code> and <code>height</code> attributes to reserve layout space and prevent the page from jumping as images load.
- **Captions on at least three images** using <code>&lt;figure&gt;</code> and <code>&lt;figcaption&gt;</code>. Remember: the
<code>alt</code> text stands in for the image when it cannot be seen; the caption gives extra context to everyone.
- **One decorative image** <code>&lt;video&gt;</code> with <code>controls</code>, a <code>poster</code> image, and fallback text between the opening and closing tags. If you do not have a video file, use any small <code>.mp4</code> you have on your computer; the player UI will still appear from the markup alone.
- **Head metadata**: Set <code>&lt;title&gt;</code>, <code>&lt;meta charset&gt;</code>, and <code>&lt;meta viewport&gt;</code>.

Full details of the project is linked here: [Photo Showcase](https://roadmap.sh/projects/photo-showcase)

# Screenshot of completed project
![Screenshot of Photo Showcase Project](/images/Project_Screenshot.png)

Live demo is here if interested! [Project Demo](https://ronnierods.github.io/photo-showcase/)