firebase
========

CodeIgniter Firebase Library

$this->load->spark('firebase/0.0.1');
$this->firebase->initialize(array(
    'app_path'   => '<Firebase path Here>',
    'app_key'  => '<Secret Key Here>',
));

/**
 * Use the set method
 * $this->firebase->set(<path>, [data]);
 */
