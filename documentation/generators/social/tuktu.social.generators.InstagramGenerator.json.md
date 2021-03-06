### tuktu.social.generators.InstagramGenerator
Fetches all posts matching a given keyword.

  * **nodes** *(type: array)* `[Optional]`
  - Optionally specify on which nodes to run and how many instances you want on each node.

    * **[UNNAMED]** *(type: object)* `[Required]`

      * **type** *(type: string)* `[Required]`
      - The type of node handler, one of SingleNode, SomeNodes, AllNodes (leave empty for local execution)

      * **nodes** *(type: string)* `[Required]`
      - The nodes to use for this node handler type

      * **instances** *(type: int)* `[Optional, default = 1]`
      - The amount of instances per node of this handler type

  * **result** *(type: string)* `[Required]`

  * **stop_on_error** *(type: boolean)* `[Optional, default = true]`
  - If set to false, Tuktu will not kill the flow on data error.

  * **config** *(type: object)* `[Required]`

    * **key** *(type: string)* `[Required]`
    - The ID for the application.

    * **secret** *(type: string)* `[Required]`
    - The secret for the application.

    * **token** *(type: string)* `[Required]`
    - The access token.

    * **keyword** *(type: string)* `[Required]`
    - The keyword to search for.

