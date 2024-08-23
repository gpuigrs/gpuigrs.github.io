---
title: Contacte
icon: fas fa-envelope
order: 5
---
<div style="text-align:center;">
<a class="boto" style="width:50%;font-size:1.5em;" href="tel:+34679259402"><i class="fa-solid fa-phone"></i>⠀Truca'ns</a>

<a class="boto" style="background-color:#25d366;width:50%;font-size:1.5em;" href="https://wa.me/+34679259402"><i class="fa-brands fa-whatsapp"></i>⠀Escriu-nos per whatsapp</a>
</div>

<section style="width: 100%; max-width: 40rem;margin-left: auto;margin-right: auto;padding: 3rem 1rem;">
  <div style="margin-top: 1rem;">
    <h2 style="  font-size: 1.875rem;line-height: 2.25rem;font-weight: 700;text-align:center;">Escriu-nos un correu</h2>
    <p style="color: rgb(107 114 128);text-align:center;">
      Omple aquest formulari i de seguida ens posarem en contacte amb tu!
    </p>
  </div>

  <form class="contact-form" action="https://api.web3forms.com/submit" method="POST">

    <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE" />
    <input type="hidden" name="subject" value="Nou missatge de la pàgina web" />
    <input type="hidden" name="from_name" value="Pàgina web" />
    <!-- More custom ization options available in the docs: https://docs.web3forms.com -->
      <div style="display: grid; gap: 1rem;margin-top: 2rem;">
      <div style="display: flex;flex-direction: column;">
        <label for="name" style="margin-bottom:0.5rem;">Nom i cognoms</label>
        <input id="name" name="name" style="padding: 0.5rem;border: 1px solid #e5e7eb;display: flex;height: 2.5rem;width: 100%;border-radius: 0.375rem;font-size: 0.875rem;line-height: 1.25rem;" placeholder="Nom Cognom" type="text" />
      </div>
      <div class="form-group">
        <label for="email" class="form-label">Correu electrònic</label>
        <input id="email" name="email" style="padding: 0.5rem;border: 1px solid #e5e7eb;display: flex;height: 2.5rem;width: 100%;border-radius: 0.375rem;font-size: 0.875rem;line-height: 1.25rem;" placeholder="elteu@correuelectronic.cat" type="email" />
      </div>
      <div class="form-group">
        <label for="phone" class="form-label">Núm. telèfon</label>
        <input id="phone" name="phone" style="padding: 0.5rem;border: 1px solid #e5e7eb;display: flex;height: 2.5rem;width: 100%;border-radius: 0.375rem;font-size: 0.875rem;line-height: 1.25rem;" placeholder="+34 654 33 22 11" type="text" />
      </div>
      <div class="form-group">
        <label for="message" class="form-label">Missatge</label>
        <textarea style="padding: 0.5rem;border: 1px solid #e5e7eb;display: flex;height: 2.5rem;width: 100%;border-radius: 0.375rem;font-size: 0.875rem;line-height: 1.25rem;" id="message" name="message" placeholder="Escriu aquí"></textarea>
      </div>
    </div>
    <button style="width: 100%;margin-top: 1.2rem;background-color: #2c77a1;color: #fff;padding: 13px 5px;border-radius: 0.375rem;" type="submit">Enviar missatge</button>
  </form>

</section>

