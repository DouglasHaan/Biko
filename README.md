<!-- Biko American Cuisine — Wix-aligned, mobile-first (no external files) -->
<section class="bk" style="--blue:#0f2a6b;--blue2:#1e3a8a;--red:#e11d48;--ink:#0b1220;--line:#e5e7eb;--radius:14px;--max:1000px; font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif; color:#fff; background:var(--blue); margin:0; padding:0;">
  <style>
    /* Scope everything to .bk to avoid Wix style collisions */
    .bk, .bk *{box-sizing:border-box}
    .bk a{text-decoration:none}

    /* Containers */
    .bk-wrap{max-width:var(--max);margin:0 auto;padding:56px 18px}
    .bk-row{display:flex;gap:12px;flex-wrap:wrap;align-items:center}
    .bk-stack-2{display:grid;gap:12px;grid-template-columns:1fr 1fr}
    .bk-card{background:#fff;border:1px solid var(--line);border-radius:var(--radius);color:var(--ink);box-shadow:0 6px 16px rgba(2,6,23,.08)}
    .bk-card > * {max-width:100%}
    .bk-pill{display:inline-flex;align-items:center;gap:8px;border:2px solid var(--red);background:#fff;color:var(--blue);border-radius:12px;padding:10px 14px;font-weight:900;letter-spacing:.4px;font-size:22px}
    .bk-title{font-weight:900;font-size:26px;color:var(--blue)}
    .bk-btn{display:inline-flex;align-items:center;justify-content:center;font-weight:800;border-radius:12px;padding:12px 16px;white-space:nowrap}
    .bk-btn-primary{background:var(--red);color:#fff;box-shadow:0 8px 20px rgba(225,29,72,.28)}
    .bk-btn-ghost{border:2px solid #fff;color:#fff}
    .bk-underline{height:4px;background:linear-gradient(90deg,var(--red),#ff6b8a);border-radius:2px}

    /* Header */
    .bk-header{background:#fff;border-bottom:4px solid var(--red);width:100%}
    .bk-header-in{max-width:var(--max);margin:0 auto;padding:18px;display:flex;flex-wrap:wrap;gap:12px;align-items:center;justify-content:space-between}
    .bk-nav{display:flex;gap:8px;flex-wrap:wrap}

    /* Hero */
    .bk-hero{text-align:center}
    .bk-hero h1{font-size:clamp(30px,6vw,50px);line-height:1.1;margin:0 0 10px;font-weight:900}
    .bk-hero p{max-width:740px;margin:0 auto 16px;color:#f8fafc}
    .bk-kpis{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-top:12px}
    .bk-kpi{border:1px solid var(--red);border-radius:12px;background:#fff;color:var(--ink);padding:12px 10px;text-align:center}
    .bk-kpi b{display:block;font-size:22px;color:var(--red)}

    /* Section heads */
    .bk-head{display:flex;align-items:flex-end;justify-content:space-between;gap:12px;margin-bottom:10px}
    .bk-head h2{font-size:clamp(22px,4.5vw,32px);margin:0 0 6px 0;color:#fff}

    /* Menu */
    .bk-menu-sec{background:#fff;color:var(--ink)}
    .bk-menu-sec .bk-wrap{padding-top:76px}
    .bk-cat{font-weight:900;margin:18px 0 8px;color:#0f172a}
    .bk-menu-grid{display:grid;gap:10px;grid-template-columns:1fr 1fr}
    .bk-menu-item{border:1px dashed #d1d5db;border-radius:12px;padding:12px}
    .bk-menu-top{display:flex;align-items:center;justify-content:space-between;gap:10px}
    .bk-price{color:var(--red);font-weight:900}

    /* About / Story */
    .bk-about{background:var(--blue2); position:relative; isolation:isolate;}
    .bk-story{display:grid;gap:14px;grid-template-columns:1.1fr .9fr; align-items:start}
    .bk-story .bk-card{padding:18px; display:block; width:100%; overflow:visible}
    .bk-quote{font-style:italic;color:#e5e7eb}
    .bk-about p{color:#0f172a}

    /* Community */
    .bk-locs{background:#16306c}
    .bk-locs p{color:#f8fafc}
    .bk-badges{display:flex;gap:8px;flex-wrap:wrap}
    .bk-badge{border:1px solid #c7d2fe;background:#eef2ff;color:#1e3a8a;border-radius:999px;padding:6px 10px;font-size:12px;font-weight:800}

    /* CTA */
    .bk-cta{background:linear-gradient(180deg,#0f2a6b 0%, #0a1d4f 100%);border-top:1px solid rgba(255,255,255,.12)}
    .bk-cta p{color:#0f172a}

    /* Footer */
    .bk-footer{background:#0a1d4f;text-align:center;font-size:14px}

    /* Mobile helpers to avoid overlap in Wix */
    @media (max-width:860px){
      .bk-stack-2{grid-template-columns:1fr}
      .bk-menu-grid{grid-template-columns:1fr}
      .bk-kpis{grid-template-columns:1fr 1fr}
      .bk-header-in{justify-content:center;text-align:center}
      .bk-nav{justify-content:center}
      /* Make About a strict vertical stack on mobile (no grid) */
      .bk-story{display:block}
      .bk-story .bk-card{margin-bottom:12px}
    }
    @media (max-width:520px){
      .bk-kpis{grid-template-columns:1fr 1fr}
    }
  </style>

  <!-- HEADER -->
  <header class="bk-header">
    <div class="bk-header-in">
      <div class="bk-row" style="gap:14px">
        <span class="bk-pill">BIKO</span>
        <span class="bk-title">American Cuisine</span>
      </div>
      <nav class="bk-nav">
        <a class="bk-btn bk-btn-ghost" href="#menu">Menu</a>
        <a class="bk-btn bk-btn-ghost" href="#about">About</a>
        <a class="bk-btn bk-btn-primary" href="#order">Order Now</a>
      </nav>
    </div>
  </header>

  <!-- HERO -->
  <section class="bk-hero bk-wrap">
    <h1>Gourmet Burgers <span style="color:var(--red)">on Wheels</span></h1>
    <p>Gourmet burgers, stacked sandwiches, and golden fries — proudly served with American pride across Eagle Mountain.</p>
    <div class="bk-row" style="justify-content:center;margin-top:8px">
      <a class="bk-btn bk-btn-primary" href="#menu">See Full Menu</a>
      <a class="bk-btn bk-btn-ghost" href="#catering">Catering</a>
    </div>
    <div class="bk-kpis">
      <div class="bk-kpi"><b>30+ Years</b><span>Chef Experience</span></div>
      <div class="bk-kpi"><b>1000s</b><span>Happy Guests</span></div>
      <div class="bk-kpi"><b>5★</b><span>Local Favorite</span></div>
    </div>
  </section>

  <!-- ORDER -->
  <section id="order" class="bk-wrap bk-card" style="display:flex;align-items:center;justify-content:space-between;gap:12px;flex-wrap:wrap">
    <p style="margin:0;color:#111827;font-weight:700">Order pickup now or schedule ahead.</p>
    <div class="bk-row">
      <a class="bk-btn bk-btn-primary" href="https://www.toasttab.com/local/order/biko-american-cuisine/r-bfd7a693-4283-4d84-aa7d-cbddbee0d6c6" target="_blank" rel="noopener">Order on Toast</a>
      <a class="bk-btn" style="border:2px solid var(--red);color:var(--red)" href="#" target="_blank" rel="noopener">Order on DoorDash</a>
    </div>
  </section>

  <!-- MENU -->
  <section id="menu" class="bk-menu-sec">
    <div class="bk-wrap">
      <div class="bk-head">
        <div>
          <h2>Full Menu</h2>
          <div class="bk-underline"></div>
        </div>
        <a class="bk-btn bk-btn-primary" href="#order">Order Now</a>
      </div>

      <div class="bk-cat">Combos (Burger + Fries + Drink)</div>
      <div class="bk-menu-grid">
        <div class="bk-menu-item">
          <div class="bk-menu-top"><strong>Combo Bacon Cheeseburger</strong><span class="bk-price">$17.00</span></div>
          <p style="margin:.4rem 0 0;color:#0f172a">Crisp bacon, American cheese, pickles, house sauce. Includes fries & drink.</p>
        </div>
        <div class="bk-menu-item">
          <div class="bk-menu-top"><strong>Combo Double Cheeseburger</strong><span class="bk-price">$17.00</span></div>
          <p style="margin:.4rem 0 0;color:#0f172a">Two juicy patties, double cheese, Biko sauce. Includes fries & drink.</p>
        </div>
        <div class="bk-menu-item">
          <div class="bk-menu-top"><strong>Mushroom Swiss Burger</strong><span class="bk-price">$17.00</span></div>
          <p style="margin:.4rem 0 0;color:#0f172a">Sautéed mushrooms, Swiss, caramelized onions, garlic aioli.</p>
        </div>
        <div class="bk-menu-item">
          <div class="bk-menu-top"><strong>Quarter Pound Cheeseburger</strong><span class="bk-price">$14.00</span></div>
          <p style="margin:.4rem 0 0;color:#0f172a">Classic quarter-pound, American cheese, lettuce, tomato, pickles.</p>
        </div>
      </div>

      <div class="bk-cat">Fries & Sides</div>
      <div class="bk-menu-grid">
        <div class="bk-menu-item">
          <div class="bk-menu-top"><strong>Garlic Fries</strong><span class="bk-price">$6.00</span></div>
          <p style="margin:.4rem 0 0;color:#0f172a">Hand-cut fries tossed in garlic butter & parsley.</p>
        </div>
        <div class="bk-menu-item">
          <div class="bk-menu-top"><strong>Plain Fries</strong><span class="bk-price">$6.00</span></div>
          <p style="margin:.4rem 0 0;color:#0f172a">Crispy, golden, and perfect with our house dipping sauces.</p>
        </div>
      </div>

      <div class="bk-cat">Drinks</div>
      <div class="bk-menu-grid">
        <div class="bk-menu-item">
          <div class="bk-menu-top"><strong>Soda / Water</strong><span class="bk-price">$2.00–$3.00</span></div>
          <p style="margin:.4rem 0 0;color:#0f172a">Assorted canned sodas and bottled water.</p>
        </div>
      </div>

      <div class="bk-row" style="justify-content:center;margin-top:14px">
        <a class="bk-btn bk-btn-primary" href="#order">Order for Pickup</a>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about" class="bk-about">
    <div class="bk-wrap">
      <div class="bk-head">
        <div>
          <h2>About Biko</h2>
          <div class="bk-underline"></div>
        </div>
      </div>

      <!-- Desktop: two columns; Mobile: stacked (see media rule) -->
      <div class="bk-story">
        <!-- Story Card -->
        <div class="bk-card" style="margin-bottom:12px;">
          <h3 style="margin:0 0 8px;color:#0f172a">30 Years in the Kitchen, Still Cooking with Heart</h3>
          <p class="bk-quote">“After three decades cooking for families, teams, and neighbors, I wanted to bring a fresh,
            uniquely American food truck experience to Eagle Mountain—food that’s honest, hearty, and crafted with care.”</p>
          <p style="color:#0f172a">That vision became <strong>BIKO American Cuisine</strong>: a red-white-and-blue truck serving gourmet burgers,
            stacked sandwiches, and fries done right. Every menu item is built on fundamentals—quality ingredients,
            consistent technique, and seasoning that lets the food shine. We keep lines moving, flavors bold, and
            hospitality front and center.</p>
          <p style="color:#0f172a">From weekday lunches to Friday-night lights, from neighborhood parks to local events, our goal is simple:
            <strong>serve great food that brings people together</strong>. Thanks for welcoming us—we’re proud to call this community home.</p>
        </div>

        <!-- Badges / CTA Card -->
        <div class="bk-card" style="padding:18px; margin-bottom:12px;">
          <div class="bk-badges" style="margin-bottom:10px">
            <span class="bk-badge">Chef-Led</span>
            <span class="bk-badge">Made-to-Order</span>
            <span class="bk-badge">Family-Owned</span>
            <span class="bk-badge">Local Favorite</span>
          </div>
          <div style="border:1px dashed #cbd5e1;border-radius:12px;padding:14px;color:#0f172a;background:#f8fafc;margin-bottom:10px">
            <strong>Pro Tip:</strong> Hosting a crowd? Ask about our <em>event menu</em> with bulk fries and burger kits.
          </div>
          <a class="bk-btn bk-btn-primary" href="#catering">Ask About Catering</a>
        </div>
      </div>
    </div>
  </section>

  <!-- COMMUNITY -->
  <section id="community" class="bk-locs">
    <div class="bk-wrap">
      <div class="bk-head">
        <div>
          <h2>Proudly Serving Eagle Mountain, Utah</h2>
          <div class="bk-underline"></div>
        </div>
      </div>
      <p style="max-width:800px;margin:0 0 12px">
        You’ll spot us around The Ranches, City Center, and at neighborhood parks, school events, and weekend markets.
        We post our weekly schedule on Instagram—swing by for lunch, dinner, or a well-earned post-round bite after the
        Ranches Golf Club.
      </p>
      <div class="bk-row" style="justify-content:space-between">
        <div class="bk-badges">
          <span class="bk-badge">The Ranches</span>
          <span class="bk-badge">City Center</span>
          <span class="bk-badge">Local Events</span>
          <span class="bk-badge">Parks & Schools</span>
        </div>
        <a class="bk-btn bk-btn-ghost" href="#order">Today’s Hours</a>
      </div>
    </div>
  </section>

  <!-- CATERING -->
  <section id="catering" class="bk-cta">
    <div class="bk-wrap">
      <div class="bk-head">
        <div>
          <h2>Bring Biko to Your Event</h2>
          <div class="bk-underline"></div>
        </div>
      </div>
      <div class="bk-stack-2">
        <div class="bk-card" style="padding:16px">
          <h4 style="margin:0 0 6px;color:#0f172a">Corporate Lunches</h4>
          <p style="margin:0;color:#0f172a">Fast service, set menus, custom tickets—great for teams big and small.</p>
        </div>
        <div class="bk-card" style="padding:16px">
          <h4 style="margin:0 0 6px;color:#0f172a">School & Community</h4>
          <p style="margin:0;color:#0f172a">Fundraisers, games, festivals—we’ll tailor the menu to fit the crowd.</p>
        </div>
        <div class="bk-card" style="padding:16px">
          <h4 style="margin:0 0 6px;color:#0f172a">Private Events</h4>
          <p style="margin:0;color:#0f172a">Birthdays, reunions, and weddings—ask about per-guest pricing.</p>
        </div>
        <div class="bk-card" style="padding:16px">
          <h4 style="margin:0 0 6px;color:#0f172a">Neighborhood Nights</h4>
          <p style="margin:0;color:#0f172a">Block parties and HOA events—easy booking, reliable service.</p>
        </div>
      </div>
      <div class="bk-row" style="justify-content:center;margin-top:12px">
        <a class="bk-btn bk-btn-primary" href="#order">Check Dates</a>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bk-footer">
    <div class="bk-wrap" style="padding:24px 18px 56px">
      <div style="display:flex;justify-content:center;gap:10px;flex-wrap:wrap;margin-bottom:8px">
        <span class="bk-pill">BIKO</span>
        <span style="font-weight:800">American Cuisine</span>
      </div>
      <p style="margin:6px 0 0;color:#cbd5e1">© 2025 Biko American Cuisine • Eagle Mountain, Utah</p>
    </div>
  </footer>
</section>

   
