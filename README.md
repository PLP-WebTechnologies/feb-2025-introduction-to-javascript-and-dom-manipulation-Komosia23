<!DOCTYPE html>
<html>
<head>
  <title>Text Content Example</title>
</head>
<body>
  <p id="targetElement">Original Text</p>
  <button onclick="changeText()">Change Text</button>
  <script src="script.js"></script>
</body>
</html>
 html>
<html>
<head>
  <title>Style Modification Example</title>
</head>
<body>
  <p id="targetElement">Styled Element</p>
  <button onclick="applyStyles()">Apply Styles</button>
  <script src="script.js"></script>
</body>
<!DOCTYPE html>
<html>
<head>
  <title>Add/Remove Element Example</title>
</head>
<body>
  <div id="container">
    <p>Container Element</p>
  </div>
  <button onclick="toggleElement()">Add Element</button>
  <script src="script.js"></script>
</body>
</html>
<section id="elements">
            <h2>Common HTML Elements</h2>
            <article>
                <h3>Text Elements</h3>
                <p>HTML provides various elements for text formatting:</p>
                <ul>
                    <li><strong>Strong text</strong> for importance</li>
                    <li><em>Emphasized text</em> for emphasis</li>
                    <li><mark>Highlighted text</mark> to mark or highlight</li>
                    <li><code>Code elements</code> for displaying code</li>
                </ul>
            </article>
        </section>
        
        <section id="semantic">
            <h2>Semantic HTML</h2>
            <p>Semantic HTML elements clearly describe their meaning to both the browser and the developer.</p>
            
            <aside>
                <h3>Why Use Semantic HTML?</h3>
                <p>Semantic elements provide better accessibility, improve SEO, and make your code easier to read and maintain.</p>
            </aside>
            
            <p>Examples of semantic elements include:</p>
            <ol>
                <li>&lt;header&gt; - Defines a header for a document or section</li>
                <li>&lt;nav&gt; - Defines navigation links</li>
                <li>&lt;section&gt; - Defines a section in a document</li>
                <li>&lt;article&gt; - Defines an independent, self-contained content</li>
                <li>&lt;footer&gt; - Defines a footer for a document or section</li>
            </ol>
        </section>
        
<section id="form">
            <h2>Form Example</h2>
            <form>
                <fieldset>
                    <legend>Contact Information</legend>
                    <div>
                        <label for="name">Name:</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div>
                        <label for="email">Email:</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div>
                        <label for="message">Message:</label>
                        <textarea id="message" name="message" rows="4"></textarea>
                    </div>
                    <div>
                        <label for="interest">Interest:</label>
                        <select id="interest" name="interest">
                            <option value="learning">Learning HTML</option>
                            <option value="development">Web Development</option>
                            <option value="design">Web Design</option>
                        </select>
                    </div>
                    <div>
                        <button type="submit">Submit</button>
                        <button type="reset">Reset</button>
                    </div>
                </fieldset>
            </form>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2025 HTML5 Structure Demo | Created as an example of semantic HTML</p>
    </footer>
</body>
</html>
