# About me

<style>
.author-wrapper {
  margin-top: 24px;
  margin-bottom: 32px;
}

.author-top {
  display: flex;
  gap: 32px;
  align-items: stretch; /* photo column stretches to the info-box height */
  flex-wrap: wrap;
}

.author-photo-wrap {
  flex: 0 0 320px;
  max-width: 320px;

  /* Make the inner photo fill the full height of this column */
  display: flex;
  align-items: stretch;
}

/* Photo as a background so it DOES NOT set the row height */
.author-photo {
  flex: 1;
  border-radius: 16px;
  box-shadow: 0 8px 24px rgba(0, 0, 0, 0.18);

  background-image: url("images/author.png");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;

  /* Fallback for narrow screens when blocks wrap */
  min-height: 220px;
}

.author-right {
  flex: 1 1 320px;
  min-width: 280px;
  padding: 18px 22px;
  border-radius: 14px;
  background: rgba(127, 127, 127, 0.08);

  /* IMPORTANT: NO vertical stretching here */
  /* (so this block defines the height naturally) */
}

.author-info-line {
  margin: 0;
  font-size: 1.02rem;
  line-height: 1.6;
}

.author-bio {
  margin-top: 20px;
  width: 100%;
  box-sizing: border-box;
  padding: 18px;
  border-radius: 14px;
  background: rgba(127, 127, 127, 0.08);
  line-height: 1.7;
  text-align: justify;
}

.sections-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.section-card {
  display: block;
  padding: 24px;
  border-radius: 16px;
  text-decoration: none !important;
  color: inherit !important;
  background: rgba(127, 127, 127, 0.08);
  border: 1px solid rgba(127, 127, 127, 0.18);
  transition: transform 0.2s ease, box-shadow 0.2s ease, background 0.2s ease;
  font-size: 1.1rem;
  font-weight: 600;
}

.section-card:hover {
  background: rgba(255, 215, 0, 0.18);
  box-shadow: 0 10px 28px rgba(255, 215, 0, 0.22);
  transform: translateY(-3px);
}

.section-card-title {
  margin-bottom: 8px;
}

.section-card-desc {
  font-size: 0.95rem;
  font-weight: 400;
  line-height: 1.5;
  opacity: 0.9;
}
</style>

<div class="author-wrapper">
  <div class="author-top">
    <div class="author-photo-wrap">
      <div class="author-photo" role="img" aria-label="Author photo"></div>
    </div>

    <div class="author-right">
      <p class="author-info-line"><strong>Name:</strong> Nikita Okunev </p>
      <p class="author-info-line"><strong>Status:</strong> Bachelor student of ITMO, 1st year</p>
      <p class="author-info-line"><strong>Age:</strong> 19</p>
      <p class="author-info-line"><strong>Occupation:</strong> programmer</p>
      <p class="author-info-line"><strong>E-mail:</strong> nicholas_chebski@outlook.com</p>
      <p class="author-info-line"><strong>Phone number:</strong> +7 (921) 450-05-38</p>
    </div>
  </div>

  <div class="author-bio">
    <p><strong>More information about me</strong></p>

    <p>
      <em>
        [There would be more.]
      </em>
    </p>
  </div>
</div>

# Travel to:

<div class="sections-grid">
  <a class="section-card" href="study/">
    <div class="section-card-title">Study projects</div>
    <div class="section-card-desc">
      There are my projects from university.
    </div>
  </a>

  <a class="section-card" href="unstudy/">
    <div class="section-card-title">Other projects</div>
    <div class="section-card-desc">
      It is empty for now.
    </div>
  </a>
</div>