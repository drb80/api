# api
A simple RoR To Do list backend for different frontends

    rails new API --api --skip-action-mailbox --skip-active-storage
    cd API
    bundle add faker
    rails generate scaffold Item what:string when:date
    rails db:migrate
    rails db:seed
