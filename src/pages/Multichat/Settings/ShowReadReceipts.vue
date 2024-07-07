<template>
  <MainLayout>
    <header class="mv-header mv-header-bg px-3 px-sm-4">
      <h1 class="text-primary fw-bold">MultiChat Settings</h1>
      <p class="text-dark fw-bold">Adjust Your Messages Settings</p>
    </header>

    <main class="container px-4 py-2 my-4 py-md-5 my-md-2">
      <div class="card mb-3">
        <div class="card-header">
          <h3 class="text-primary fw-bold">Show Read Receipts</h3>
        </div>
        <div class="card-body">
          <p class="text-dark mb-3">
            The "Show read receipts" setting in Multichat allows you to control whether people you are messaging with can see when you have viewed their messages. This setting provides you with a way to manage your communication transparency and preferences effectively.
          </p>
          <ul class="list-group">
            <li class="list-group-item">
              <p class="text-dark fw-bold">On</p>
              <p>
                When this option is enabled, people you’re messaging with will know when you’ve seen their messages. This helps to create a transparent communication flow, allowing your contacts to know that their messages have been acknowledged.
              </p>
            </li>
            <li class="list-group-item">
              <p class="text-dark fw-bold">Off</p>
              <p>
                When this option is disabled, people you’re messaging with will not know when you’ve seen their messages. This setting offers you more privacy, as it allows you to read messages without notifying the sender that you have seen them.
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
            <li class="multividas-list-item">Go to the "Show read receipts" section.</li>
            <li class="multividas-list-item">Toggle the option to On or Off based on your preference.</li>
            <li class="multividas-list-item">Your changes will be saved automatically, and the new setting will be applied immediately.</li>
          </ul>
        </div>
      </div>

      <div class="card p-3 mb-3">
        <p class="text-dark fw-bold mb-2">Important Notes</p>
        <p class="text-dark">
          Read receipts are not shown on message requests. This ensures that you maintain privacy when dealing with unsolicited messages or requests from unknown sources.
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
