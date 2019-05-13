# Generate-Random-password-generator
How to generate Random password with all related character and letters

private function password_generate($chars) {
    $data = '1234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ!@#$%^&*-abcefghijklmnopqrstuvwxyz';
    return substr(str_shuffle($data), 0, $chars);
}

echo $get_password = $this->password_generate(8); // 8 indicate length
