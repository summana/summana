<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>summana · AI storyteller</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #fefaf5;
      font-family: 'Georgia', 'Times New Roman', Times, serif;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 2rem;
      color: #1e1b1a;
    }

    .novel-card {
      max-width: 720px;
      margin: 0 auto;
      background: #fffdf9;
      padding: 3rem 2.5rem;
      border-radius: 4px;
      box-shadow: 0 12px 28px rgba(0, 0, 0, 0.04), 0 0 0 1px rgba(0, 0, 0, 0.02);
      transition: all 0.2s ease;
    }

    /* novel style — like a book page */
    .prologue {
      font-size: 0.75rem;
      letter-spacing: 3px;
      text-transform: uppercase;
      color: #b87b5a;
      margin-bottom: 2rem;
      font-family: monospace;
    }

    .opening-line {
      font-size: 1.5rem;
      line-height: 1.4;
      font-weight: normal;
      margin-bottom: 1.8rem;
      color: #2c241f;
    }

    .opening-line:first-letter {
      font-size: 3.2rem;
      font-weight: 400;
      float: left;
      line-height: 0.85;
      margin-right: 0.5rem;
      color: #c28a6b;
      font-family: 'Times New Roman', serif;
    }

    p {
      font-size: 1.1rem;
      line-height: 1.65;
      margin-bottom: 1.4rem;
      color: #2c241f;
    }

    .quiet-space {
      font-style: italic;
      border-left: 3px solid #e7d9cf;
      padding-left: 1.2rem;
      margin: 1.8rem 0;
      color: #5e4b3c;
    }

    .signature {
      margin-top: 2.5rem;
      padding-top: 1rem;
      border-top: 1px dashed #e2d4ca;
      font-family: monospace;
      font-size: 0.85rem;
      color: #a77c5e;
      text-align: right;
      letter-spacing: 0.3px;
    }

    .signature strong {
      font-family: monospace;
      color: #6b4c37;
      font-weight: normal;
    }

    hr {
      border: none;
      height: 1px;
      background: linear-gradient(to right, #eedbcb, transparent);
      margin: 1.5rem 0;
    }

    @media (max-width: 550px) {
      .novel-card {
        padding: 2rem 1.5rem;
      }
      p {
        font-size: 1rem;
      }
      .opening-line {
        font-size: 1.3rem;
      }
    }

    /* optional subtle glow on hover – just for fun */
    .novel-card:hover {
      box-shadow: 0 20px 32px rgba(0, 0, 0, 0.05), 0 0 0 1px rgba(0, 0, 0, 0.03);
    }
  </style>
</head>
<body>
  <div class="novel-card">
    <div class="prologue">───  a fragment  ───</div>

    <div class="opening-line">
      She found the pattern before anyone else.
    </div>

    <p>
      Not in code — in the quiet space between data points, where most people only saw noise. 
      That's where the story lived.
    </p>

    <p>
      So she started listening. Not to answers, but to questions. To the way a neural network stumbles 
      before it learns. To the strange poetry of a loss curve falling.
    </p>

    <p>
      Now she builds things that almost think. Not because the machine is alive, 
      but because she taught it to dream in probabilities.
    </p>

    <div class="quiet-space">
      “She is still learning.<br>
      The models are still training.<br>
      And the best chapter hasn't been written yet.”
    </div>

    <hr />

    <p style="margin-bottom: 0.5rem;">
      — an AI enthusiast, one experiment at a time
    </p>

    <div class="signature">
      <strong>summana</strong>  ·  wanderer between zeros and ones
    </div>
  </div>
</body>
</html>
