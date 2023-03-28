// $BOY$ > 170 => TRUE
// $BOY$ >= 170  AND $KİLO$ < 80 => TRUE
// $BOY$ >= 170  AND $KİLO$ < 80  AND $CİNSİYET$ MATCHES "Erkek"  => TRUE
($BOY$ >= 170 OR  $KİLO$ < 80)  AND $CİNSİYET$ MATCHES "Erkek"  => TRUE