Issue what I have found when integrating with Solidus
  bundle exec rake db:migrate

WARN  DurableDecorator: Spree::Shipment#after_ship decoration uses an invalid SHA. The original method definition could have been tampered with!
WARN  DurableDecorator: Expected SHA was 5401c76850xxxxxxxxxxxxxxxxxxxxx but the provided SHA is e8eca7f8a50ad8xxxxxxxxxxxxxxxxxxxxxxxx



------------

when working with Spree 3.0.4
NoMethodError in Spree::Admin::Shipments#index, as discussed https://github.com/spree-contrib/spree_drop_ship/issues/73
