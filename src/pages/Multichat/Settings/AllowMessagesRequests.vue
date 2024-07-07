<template>
  <MainLayout>
    <header class="mv-header mv-header-bg px-3 px-sm-4">
      <h1 class="text-primary fw-bold">MultiChat Settings</h1>
      <p class="text-dark fw-bold">Adjust Your Messages Settings</p>
    </header>

    <main class="container px-4 py-2 my-4 py-md-5 my-md-2">
      <div class="card mb-3">
        <div class="card-header">
          <h3 class="text-primary fw-bold">Allow Message Requests From</h3>
        </div>
        <div class="card-body">
          <p class="text-dark mb-3">
            The "Allow message requests from" setting in Multichat allows you to control who can send you message requests. This setting provides you with three options to manage your privacy and communication preferences effectively.
          </p>
          <ul class="list-group">
            <li class="list-group-item">
              <p class="text-dark fw-bold">No one</p>
              <p>
                Selecting this option means you will not receive message requests from anyone except for the people you follow. This is the strictest privacy setting, ensuring that only your followed contacts can message you.
              </p>
            </li>
            <li class="list-group-item">
              <p class="text-dark fw-bold">Verified users</p>
              <p>
                By choosing this option, you will allow message requests only from verified users. Verified users are accounts that have been authenticated and recognized for their credibility within the community. This setting offers a balanced approach between privacy and receiving messages from trustworthy sources.
              </p>
            </li>
            <li class="list-group-item">
              <p class="text-dark fw-bold">Everyone</p>
              <p>
                This option allows anyone to send you message requests. While this setting provides the maximum reach and interaction, it might also result in receiving messages from unknown or unsolicited sources. However, rest assured that people you follow will always be able to message you directly.
              </p>
            </li>
          </ul>
        </div>
      </div>

      <div class="card mb-3">
        <div class="card-header">
          <h3 class="text-primary fw-bold">How to Change Your Setting</h3>
        </div>
        <div class="card-body">
          <ul class="multividas-list mx-3">
            <li class="multividas-list-item">Navigate to the <a href="https://multividas.com/multichat/settings"><span class="text-decoration-underline fw-bold">Multichat Settings</span></a>.</li>
            <li class="multividas-list-item">Go to the "Allow message requests from" section.</li>
            <li class="multividas-list-item">Select the desired option (No one, Verified users, Everyone).</li>
            <li class="multividas-list-item">Your changes will be saved automatically, and the new setting will be applied immediately.</li>
          </ul>
        </div>
      </div>

      <div class="card p-3 mb-3">
        <p class="text-dark fw-bold mb-2">Important Notes</p>
        <p class="text-dark">
          People you follow will always be able to message you regardless of the option you choose. This ensures that you maintain open communication with your trusted contacts.
        </p>
      </div>
    </main>
  </MainLayout>
</template>

<script>
export default {
  metaInfo: {
    title: "MultiChat Settings",
  },
};
</script>
