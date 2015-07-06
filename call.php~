
<?php
// Get the PHP helper library from twilio.com/docs/php/install
require_once('twilio/Services/Twilio.php'); // Loads the library
 
// Your Account Sid and Auth Token from twilio.com/user/account
$sid = "AC38fd601813d752abbcd5f7245e86e9ad"; 
$token = "878ff846b0d65a0e7171c07cedfd2b97"; 
$client = new Services_Twilio($sid, $token);
 
$call = $client->account->calls->create("+1 415-599-2671", "+91 98410 76373", "http://demo.twilio.com/docs/voice.xml", array());
echo $call->sid;

?>
