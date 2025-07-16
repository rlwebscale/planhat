# Planhat API Postman Collection

This repository contains a comprehensive Postman collection for the Planhat API.

## Getting Started

To use this collection, you will need to import both the collection and the environment template into Postman.

### Prerequisites
* A Postman account.
* A Planhat account with an active API Token.

### Installation
1.  **Clone the Repository:**
    ```sh
    git clone [https://github.com/rlwebscale/planhat.git]([https://github.com/rlwebscale/planhat.git)
    ```
2.  **Import to Postman:**
    * Open Postman and click **File > Import...**.
    * Select the `Planhat API.postman_collection.json` and `Planhat.postman_environment.json` files from the cloned repository.

3.  **Configure Your Environment:**
    * In Postman, go to the **Environments** tab and select the newly imported `Planhat` environment.
    * Set the `CURRENT VALUE` for the `planhatApiToken` variable to your own Planhat API token.
    * Save the environment.

4.  **Run the Collection:**
    * Select the `Planhat` environment from the dropdown in the top-right corner and you are ready to make requests!
