<script context="module">
  export const router = false
  export const hydrate = false
</script>

<script>
  import '../app.css'
  import Section from '../lib/Section.svelte'
</script>

<Section id="register_box">
  <img
    src="/images/1_register_box.png"
    alt="register accaunt on box.com"
    style="object-fit: contain; width: 100%; justify-self: center;"
  />
  <img
    src="/images/2_see_your_shared_acoount_folder.png"
    alt="register accaunt on box.com"
    style="object-fit: contain; width: 100%; justify-self: center;"
  />
</Section>

<Section id="download_enpass">
  <img
    src="/images/3_download_enpass.png"
    alt="download enpass app"
    style="object-fit: contain; width: 100%; justify-self: center;"
  />
</Section>

<Section id="open_enpass">
  <img
    src="/images/4_open_enpass.png"
    alt="open enpass app"
    style="object-fit: contain; width: 100%; justify-self: center;"
  />
</Section>

<Section id="choose_webDAV">
  <img
    src="/images/5_choose_webDAV.png"
    alt="choose webDav"
    style="object-fit: contain; width: 100%; justify-self: center;"
  />
</Section>

<Section id="setup_webDAV">
  <img
    src="/images/6_setup_synchronization.png"
    alt="setup webDAV"
    style="object-fit: contain; width: 100%; justify-self: center;"
  />
</Section>

<Section id="master_password">
  <img
    src="/images/7_vault_master_password.png"
    alt="unload vault with master password"
    style="object-fit: contain; width: 100%; justify-self: center;"
  />
</Section>

<Section id="sync">
  <img
    src="/images/8_enable_sync.png"
    alt="enable sync feature"
    style="object-fit: contain; width: 100%; justify-self: center;"
  />
</Section>

<Section id="your_passwords">
  <img
    src="/images/9_your_shared_passwords.png"
    alt="your shared passwords"
    style="object-fit: contain; width: 100%; justify-self: center;"
  />
</Section>

<Section id="settings">
  <div style="display: flex">
    <img
      src="/images/10_setup_pin_and_other_security_options.png"
      alt="your shared passwords"
      style="object-fit: contain; width: 50%; justify-self: center;"
    />
    <img
      src="/images/11_open_enpass_settings_for_manual_sync.png"
      alt="manual sync"
      style="object-fit: contain; width: 50%; justify-self: center;"
    />
  </div>
</Section>
