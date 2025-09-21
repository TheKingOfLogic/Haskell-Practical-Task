-- HC2_AllTasks.hs

-- HC2T2 - Function Type Signatures
add :: Int -> Int -> Int
add x y = x + y

isEven :: Int -> Bool
isEven x = even x

concatStrings :: String -> String -> String
concatStrings x y = x ++ y

-- HC2T3 - Immutable Variables
myAge :: Int
myAge = 22

piValue :: Double
piValue = 3.142

greeting :: String
greeting = "Hello"

isHaskellFun :: Bool
isHaskellFun = True

-- HC2T5 - Defining Functions
circleArea :: Float -> Float
circleArea x = 3.142 * x ** 2

maxOfThree :: Int -> Int -> Int -> Int
maxOfThree x y z = max x (max y z)

-- HC2T6 - Int vs Integer
smallNumber :: Int
smallNumber = 2 ^ 62

bigNumber :: Integer
bigNumber = 2 ^ 127

-- HC2T7 - Boolean Expressions will be inside main

-- One main function for all tasks
main :: IO ()
main = do
    -- HC2T1 - Type checking is usually done in GHCi with :type
    putStrLn "HC2T1 - Type checking in GHCi (use :type in GHCi)"

    -- HC2T2 - Function usage
    putStrLn ("\nHC2T2 - Function Type Signatures:")
    putStrLn ("add 10 10 = " ++ show (add 10 10))
    putStrLn ("isEven 3 = " ++ show (isEven 3))
    putStrLn ("concatStrings \"Hask\" \"ell\" = " ++ show (concatStrings "Hask" "ell"))

    -- HC2T3 - Immutable variables
    putStrLn ("\nHC2T3 - Immutable Variables:")
    putStrLn ("myAge = " ++ show myAge)
    putStrLn ("piValue = " ++ show piValue)
    putStrLn ("greeting = " ++ greeting)
    putStrLn ("isHaskellFun = " ++ show isHaskellFun)

    -- HC2T4 - Infix vs Prefix
    putStrLn ("\nHC2T4 - Infix vs Prefix:")
    -- Prefix
    putStrLn ("5 + 3 = " ++ show ((+) 5 3))
    putStrLn ("10 * 4 = "++ show ((*) 10 4))
    putStrLn ("True && False = "++ show ((&&) True False))
    -- Infix
    putStrLn ("(+) 7 2 = "++ show (7 + 2))
    putStrLn ("(*) 6 5 = "++ show (6 * 5))
    putStrLn ("(&&) True False = "++ show (True && False))

    -- HC2T5 - Defining and using functions
    putStrLn ("\nHC2T5 - Defining and Using Functions:")
    putStrLn ("circleArea 10 = " ++ show (circleArea 10))
    putStrLn ("circleArea 20 = " ++ show (circleArea 20))
    putStrLn ("maxOfThree 10 20 30 = " ++ show (maxOfThree 10 20 30))
    putStrLn ("maxOfThree 5 10 15 = " ++ show (maxOfThree 5 10 15))

    -- HC2T6 - Int vs Integer
    putStrLn ("\nHC2T6 - Int vs Integer:")
    putStrLn ("smallNumber (Int 2^62) = " ++ show smallNumber)
    putStrLn ("bigNumber   (Integer 2^127) = " ++ show bigNumber)
    putStrLn ("2^64 :: Int (overflow) = " ++ show (2^64 :: Int))
    putStrLn ("2^64 :: Integer (correct) = " ++ show (2^64 :: Integer))

    -- HC2T7 - Boolean expressions
    putStrLn ("\nHC2T7 - Boolean Expressions:")
    putStrLn ("True using && = " ++ show (True && True))
    putStrLn ("False using || = " ++ show (False || False))
    putStrLn ("True using not = " ++ show (not False))
    putStrLn ("Comparison returning False (5 > 10) = " ++ show (5 > 10))
