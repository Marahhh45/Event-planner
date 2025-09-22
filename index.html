<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Event Reservations</title>
<style>
  :root{
    --primary:#5D3FD3;
    --secondary:#004e89;
    --light:#f7f7f7;
    --dark:#222;
  }
  body{
    margin:0;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background:var(--light);
    color:var(--dark);
  }
  header{
    background:linear-gradient(135deg,var(--primary),#5D3FD3);
    padding:20px;
    text-align:center;
    color:white;
    box-shadow:0 3px 6px rgba(0,0,0,0.2);
  }
  header h1{margin:0;font-size:2.2rem;}
  header p{margin-top:6px;font-size:1rem;}
  .container{max-width:1200px;margin:auto;padding:20px;}

  .grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:20px;
  }
  .card{
    background:white;
    border-radius:12px;
    overflow:hidden;
    box-shadow:0 4px 10px rgba(0,0,0,0.1);
    transition:transform 0.3s;
  }
  .card:hover{transform:translateY(-5px);}
  .card img{
    width:100%;
    height:300px;
    object-fit:cover;
  }
  .card-content{padding:16px;}
  .card-content h3{margin:0 0 8px;}
  .card-content p{margin:0 0 12px;font-size:0.9rem;color:#555;}
  .reserve-btn{
    display:inline-block;
    background:var(--secondary);
    color:white;
    padding:10px 16px;
    border:none;
    border-radius:6px;
    cursor:pointer;
    font-weight:bold;
  }
  .reserve-btn:hover{background:#0064b1;}

  #planEventBtn{
    position:fixed;
    bottom:25px;
    right:25px;
    background:var(--primary);
    color:white;
    padding:15px 24px;
    border:none;
    border-radius:50px;
    font-size:1rem;
    cursor:pointer;
    box-shadow:0 4px 12px rgba(0,0,0,0.2);
  }
  #planEventBtn:hover{background:#5D3FD3;}

  .modal{
    position:fixed;
    top:0;left:0;
    width:100%;height:100%;
    background:rgba(0,0,0,0.6);
    display:none;
    justify-content:center;
    align-items:center;
  }
  .modal-content{
    background:white;
    padding:24px;
    border-radius:12px;
    max-width:350px;
    width:90%;
    text-align:center;
  }
  .budget-select{
    width:100%;
    padding:10px;
    margin:15px 0;
    border:1px solid #ccc;
    border-radius:6px;
    font-size:1rem;
  }
  .close-btn{
    background:#aaa;
    border:none;
    padding:8px 14px;
    border-radius:6px;
    cursor:pointer;
    color:white;
  }
</style>
</head>
<body>

<header>
  <h1>🎉 Dream Events</h1>
  <p>Reserve an event or plan your own unforgettable experience!</p>
</header>

<div class="container">
  <div class="grid">
    <div class="card">
      <img src="summer concert 2.jpg" alt="Concert">
      <div class="card-content">
        <h3>Summer Concert</h3>
        <p>Live music festival under the stars.</p>
        <button class="reserve-btn event-btn" data-event="Summer Concert">Reserve</button>
      </div>
    </div>
    <div class="card">
      <img src="wedding 3.jpg" alt="Wedding">
      <div class="card-content">
        <h3>Elegant Wedding</h3>
        <p>Celebrate love with a classy evening reception.</p>
        <button class="reserve-btn event-btn" data-event="Elegant Wedding">Reserve</button>
      </div>
    </div>
    <div class="card">
      <img src="Corporate Event Creativity - Amazáe Events.jpeg" alt="Tech Meetup">
      <div class="card-content">
        <h3>Tech Meetup</h3>
        <p>Networking and talks with innovators.</p>
        <button class="reserve-btn event-btn" data-event="Tech Meetup">Reserve</button>
      </div>
    </div>
     <div class="card">
      <img src="birthday event.jpg" alt="Birthday Bash">
      <div class="card-content">
        <h3>Birthday Bash</h3>
        <p>Plan a fun-filled birthday celebration with music, cake, and unforgettable memories.</p>
        <button class="reserve-btn" data-event="Tech Meetup">Reserve</button>
      </div>
    </div>
    <div class="card">
        <img  src="coperate event.jpg" alt="Coperate event awards">
        <div class="card-content">
            <h3>Corporate Awards Night</h3>
            <p>Host a professional awards ceremony with dinner, trophies, and red-carpet moments.</p>
            <button class="reserve-btn" data-event="Coperate Event">Reserve</button>
        </div>
    </div>
     <div class="card">
        <img  src="gala.jpg" alt="Gala">
        <div class="card-content">
            <h3>Gala</h3>
            <p>An elegant evening of fine dining, live entertainment, and unforgettable sophistication—perfect for corporate functions, charity fundraisers, or upscale celebrations.</p>
            <button class="reserve-btn" data-event="Gala">Reserve</button>
        </div>
    </div>
  </div>
</div>

<button id="planEventBtn">📅 Plan Your Event</button>

<!-- Budget Modal -->
<div class="modal" id="budgetModal">
  <div class="modal-content">
    <h3 id="modalEvent">Reserve Event</h3>
    <p>Select your budget:</p>
    <select class="budget-select" id="budgetSelect">
      <option value="">Choose budget</option>
      <option value="₦500,000">₦500,000</option>
      <option value="₦1,000,000 - ₦5,000,000">₦1,000,000 - ₦5,000,000</option>
      <option value="₦6,000,000 - ₦10,000,000">₦6,000,000 - ₦10,000,000</option>
    </select>
    <!-- ✅ UNIQUE ID for Confirm -->
    <button id="confirmReserve" class="confirm-btn">Confirm</button><br><br>
    <button class="close-btn" id="closeModal">Cancel</button>
  </div>
</div>

<script>
document.addEventListener("DOMContentLoaded", () => {
  const reserveButtons = document.querySelectorAll('.event-btn'); // only real reserve buttons
  const modal = document.getElementById('budgetModal');
  const modalEvent = document.getElementById('modalEvent');
  const budgetSelect = document.getElementById('budgetSelect');
  const confirmReserve = document.getElementById('confirmReserve');
  const closeModal = document.getElementById('closeModal');
  let selectedEvent = '';

  reserveButtons.forEach(btn => {
    btn.addEventListener('click', () => {
      selectedEvent = btn.dataset.event;
      modalEvent.textContent = 'Reserve: ' + selectedEvent;
      budgetSelect.value = '';
      modal.style.display = 'flex';
    });
  });

  closeModal.onclick = () => modal.style.display = 'none';
  window.onclick = e => { if (e.target === modal) modal.style.display = 'none'; };

  confirmReserve.onclick = () => {
    const budget = budgetSelect.value;
    if (!budget) {
      alert('Please choose a budget first');
      return;
    }
    const phoneNumber = '2348149162514'; // ✅ replace with your number
    const message = encodeURIComponent(
      `Hello! I want to reserve the "${selectedEvent}" event. My budget is ${budget}.`
    );
    // ✅ Go directly to WhatsApp
    window.location.href = `https://wa.me/${phoneNumber}?text=${message}`;
  };

  document.getElementById('planEventBtn').onclick = () => {
    const phoneNumber = '2348149162514';
    const message = encodeURIComponent("Hi! I'd like to plan a custom event. Can we discuss options?");
    window.location.href = `https://wa.me/${phoneNumber}?text=${message}`;
  };
});
</script>

</body>
</html>
