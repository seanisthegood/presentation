<h1>Unessay Project</h1>

This Project attempts to use text from <i>The Odyessy</i> and <i>The Mahabharata</i> and compare their exploration of greatness. I performed classic "close reads" of similar passages, Book 21 from <i> The Odyessy </i> and Book 1 from <i>The Mahabharata</i>. 

<h2>Thesis Statement</h2>
<h4>
"Both <i>The Odyessy</i> and <i>The Mahabharata</i> portray greatness as a spectrum shaped by effort, divine favor, and moral identity. Specifically,  <i>The Odyessy</i> shows shows greatness from struggle whereas <i>The Mahabharata</i> shows greatness from divinity, though hard work is still a component."
</h4>

<h2>Unessay Methods</h2>
<h5>
  For the unessay project I took selections from both works and created word embeddings using the all-MiniLM-L6-v2 Model from Hugging Face, a free open-source tool: https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2#all-minilm-l6-v2. This encoded the passages. I also encoded a list of "concepts" related to greatness. I then calculated their cosine similarity and found the closest "greatness concept" for each quote. I then created the meta-data sheet so I could plug my generated embeddings into the embedddings projector. 
  Greatness Concepts: 
  <br>
  <br>
 <ul>
   <li>earned greatness</li>
  <li>effortless greatness</li>
  <li>divine greatness</li>
  <li>moral greatness</li>
  <li>heroic greatness</li>
  <li>tragic greatness</li>
  <li>trained skill</li>
  <li>divine power</li>
  <li>inner strength</li>
  <li>moral duty</li>
  <li>sacred obligation</li>
  <li>public performance</li>
  <li>heroic identity</li>
  <li>hidden suffering</li>
  <li>effortless mastery</li>
  <li>earned mastery</li>
  <li>impossible feats</li>
  <li>divine intervention</li>
  <li>human limitation</li>
  <li>overcoming doubt</li>
</ul>

</h5>
<img width="1085" height="727" alt="image" src="https://github.com/user-attachments/assets/286ca676-eecd-42c5-a1af-7b38b2e32a26" />
<b>Screenshot of the Created Projection</b>
<h3>Embeddings Projector</h3>
<h5>
  

  With the embeddings I took advantage of the Tensor Flow embeddings projector: https://projector.tensorflow.org/.
  This uses techniques like PSA, t-SNE, or UMAP to reduce the over 300 dimension embeddings and turn them into 2d or 3d renderings. The specific projection of this project is available here:
  https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/seanisthegood/presentation/main/projector_config.json
  <img width="1083" height="734" alt="image" src="https://github.com/user-attachments/assets/8f869654-c5f7-4b03-934b-c058540ea915" />
  <b>Screenshot of the Word2Vec Model Projection</b>
  <br>
  <br>
  These projections invite the user to click around and see how words and phrases exist in the vector space. For my project clicking one of the orbs reveals the closet "greatness concept" and its mathmatical similarity. 
</h5>

<h3>Further Work</h3>

<h5>
  This is my first time really taking advantage of embeddings and projecting them. I would like to see how I could compare other works to the ones I chose to see how different works and their themes can compar in this space. It was interesting to explore this kind of nexus of literature and data science. I would also work towards a more definitive understanding, as this is a representation of the embeddings, but does not offer an answer to the thesis statement. It exists as an exploration more than anything else.
</h5>
