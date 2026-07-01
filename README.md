# MLBB-TOURNAMENT
MLBB TOURNAMENT
<div class="form-row">
      <div>
        <label>WhatsApp Number <span class="required">*</span></label>
        <input type="text" name="whatsapp" id="whatsapp" placeholder="+91..." required />
      </div>
      <div>
        <label>Email (optional)</label>
        <input type="email" name="email" id="email" />
      </div>
    </div>

    <div>
      <label>Players (IGN) <span class="required">*</span></label>
      <div style="display:grid;gap:8px">
        <input type="text" name="player1" placeholder="Player 1 IGN" required />
        <input type="text" name="player2" placeholder="Player 2 IGN" required />
        <input type="text" name="player3" placeholder="Player 3 IGN" required />
        <input type="text" name="player4" placeholder="Player 4 IGN" required />
        <input type="text" name="player5" placeholder="Player 5 IGN" required />
      </div>
    </div>

    <div style="margin-top:10px">
      <label>Substitutes (IGN)</label>
      <div style="display:grid;gap:8px">
        <input type="text" name="sub1" placeholder="Substitute 1 IGN" />
        <input type="text" name="sub2" placeholder="Substitute 2 IGN" />
      </div>
    </div>

    <div style="margin-top:10px">
      <label>Upload Payment Screenshot <span class="required">*</span></label>
      <input type="file" name="payment_screenshot" id="payment_screenshot" accept="image/*,application/pdf" required />
      <div class="file-preview" id="filePreview">No file chosen</div>
    </div>

    <div style="margin-top:10px;display:flex;gap:8px;align-items:center">
      <div class="copy-upi" id="upiBox">
        <strong>UPI:</strong>&nbsp;<span id="upiId">shantibrahma@nyes</span>
      </div>
      <button type="button" class="btn" id="copyUpiSmall">Copy UPI</button>
    </div>

    <div style="margin-top:12px">
      <label>
        <input type="checkbox" id="tandc" required /> I accept the <a href="#" id="tandcLink">Terms & Conditions</a> <span class="required">*</span>
      </label>
    </div>

    <div class="form-actions">
      <button type="submit" class="btn">Submit Registration (₹500)</button>
      <button type="button" class="whatsapp" id="shareWa">Share via WhatsApp</button>
    </div>

    <div class="footer-note">
      <strong>Prizes:</strong> 🥇 ₹5,500 · 🥈 ₹2,000 · 🥉 ₹1,000 · 🎁 1 Free Slot for Upcoming Tournament
      <div style="margin-top:6px;color:var(--muted)">Contact: <span id="contactNumber">+91-XXXXXXXXXX</span></div>
    </div>
  </form>
</div>

<div class="card">
  <h3 style="margin-top:0">Event Info</h3>
  <div class="prizes">
    <div class="prize"><div>Prize Pool</div><div><strong>₹8,500</strong></div></div>
    <div class="prize"><div>Registration Fee</div><div><strong>₹500</strong></div></div>
    <div class="prize"><div>Slots</div><div><strong id="slots">Limited slots (first come, first served)</strong></div></div>
    <div style="margin-top:10px">
      <a href="#" id="posterLink">View Poster</a>
    </div>
  </div>
  <div style="margin-top:12px;font-size:13px;color:var(--muted)">
    Mobile friendly · Purple & Gold theme · Works on phones & PCs
  </div>
</div>
