# Vuex-log

Log actions & mutations in vuex! 🚀

## Usage

``` js
import { mutationLogger, actionLogger } from 'vuex-log'

const store = new Vuex.Store({
  state,
  mutations,
  plugins: [mutationLogger, actionLogger]
})

```