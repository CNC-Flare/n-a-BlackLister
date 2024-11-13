# Page For CrossPost-Auth setup


## Install

## Add Prefix
- Add [ ~~NSBlackList ] to your AutoMod Domain Blocking Rule
```

    #~~NSBlackList
    # A URL Black List create by NOO-ASK
    type: submission
    domain+body+title: []
    action: remove
    action_reason: "A {{kind}} with a link to a banned domain [{{match}}]"
    message: "Your {{kind}} was removed because we don't allow links to {{match}}."

```

## Enjoy
